crashlog
========

Modified version of crashlog.py distibuted with LLDB.framework.

Improved searching for bundles using mdimport. Also allows you to specify directery with dsysms (via the --dsyms flag) and
directory where to look for additional bundles (via the --bundles flag). The latter is especially handy when you need
to find frameworks, plugins or even other apps within another bundle. In this case just specify path to the root bundle like "--bundle /Applications/Xcode.app/"

If you need to add more than one path to dsyms or bundles, just open the script and modify DSYMS and BUNDLES globals.

Original version can be found either at /System/Library/PrivateFrameworks/LLDB.framework/Versions/A/Resources/Python/lldb/macosx/crashlog.py
or at /Applications/Xcode.app/Contents/SharedFrameworks/LLDB.framework/Resources/Python/lldb/macosx/crashlog.py
