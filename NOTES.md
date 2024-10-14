Installation on MacOS
---------------------

    brew update
    brew install powershell/tap/powershell
    brew install mono-libgdiplus
    brew install azure-cli
    brew tap azure/functions
    brew install azure-functions-core-tools@4

Needed to overwrite Python 3.12:

    lars@Larss-MBP ~ % brew link --overwrite python@2 --dry-run
    fWould remove:
    /usr/local/Frameworks/Python.framework/Headers -> /usr/local/Cellar/python@3.12/3.12.3/Frameworks/Python.framework/Headers
    /usr/local/Frameworks/Python.framework/Python -> /usr/local/Cellar/python@3.12/3.12.3/Frameworks/Python.framework/Python
    /usr/local/Frameworks/Python.framework/Resources -> /usr/local/Cellar/python@3.12/3.12.3/Frameworks/Python.framework/Resources
    /usr/local/Frameworks/Python.framework/Versions/Current -> /usr/local/Cellar/python@3.12/3.12.3/Frameworks/Python.framework/Versions/Current



Account
-------

lars.behnke@apporiented.com



Links
-----

* https://learn.microsoft.com/de-de/powershell/scripting/install/installing-powershell-on-macos?view=powershell-7.4
* https://learn.microsoft.com/en-us/dotnet/core/install/macos
* https://learn.microsoft.com/de-de/cli/azure/install-azure-cli-macos
* https://learn.microsoft.com/en-us/azure/azure-functions/functions-run-local?tabs=macos%2Cisolated-process%2Cnode-v4%2Cpython-v2%2Chttp-trigger%2Ccontainer-apps&pivots=programming-language-csharp


