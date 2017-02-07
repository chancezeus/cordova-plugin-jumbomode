#Jumbo Mode support for Cordova

This plugin adds jumboMode support to the build process, if enabled static strings (and nothing else as far as I could
find) will be indexed as 32bit indices, leaving more space in the 64k index range for methods (this could enable you to
build the app without needing multi-dex support, especially if there are a lot of static strings in the Java sources).
