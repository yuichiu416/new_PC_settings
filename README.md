# new_PC_settings
a cheetsheet for setting up a new PC

[Download VS Code](https://code.visualstudio.com/Download)

[Download Git for Windows](https://gitforwindows.org/)
   * Select `Use Git and optional Unix tools from the Command Prompt`
   * Select `Use Windows' default console window`
   * Select `Use the OpenSSL library`
   * Select `Checkout Windows-style, commit Unix-style line endings`
   * Select `Use MinTTY`
   * Select `Default (fast-forward or merge)`
   * Select `Git Credential Manager Core`
   * Select `Enable file system caching`
   * Select `Enable experimental support for pseudo consoles`

Download extensions:
 * [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)

 * [Bracket Pair Colorize](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2)

 * [Debugger for Chrome](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome)

 * [ES7 React/Redux/GraphQL/React-Native snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets)

 * [HTML Snippets](https://marketplace.visualstudio.com/items?itemName=abusaidm.html-snippets)

 * [IntelliSense for CSS](https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion)

 * [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)

 * [Markdown Preview](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)

 * [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)

 * [Ruby](https://marketplace.visualstudio.com/items?itemName=rebornix.Ruby)

 * [vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)
 
 * [PHP IntelliSense](https://marketplace.visualstudio.com/items?itemName=felixfbecker.php-intellisense)
 
 * [SSH FS](https://marketplace.visualstudio.com/items?itemName=Kelvin.vscode-sshfs)
 
 * [Git Lens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
    
[Install the Windows Subsystem for Linux](https://docs.microsoft.com/en-us/windows/wsl/install-win10)

[Install Ruby](https://rubyinstaller.org/downloads/)

[Install NPM](https://nodejs.org/en/)

[Install Adobe Reader](https://acrobat.adobe.com/us/en/acrobat/pdf-reader.html)

Install linux bash
   * Enable “Windows Subsystem for Linux” feature
      * Run WindowsPowerShell as Administrator
         *Run `Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux`, hit `Y` if prompted
   *  Download a Linux system from the Windows store
      * Select Ubuntu and install
   * Settings -> Update & Security -> For developers -> Select developer Mode
   * Control Panel -> Programs -> windows features -> Windows Subsystem for Linux
   
[Install Yarn](https://classic.yarnpkg.com/en/docs/install/#windows-stable)

Install Pip:
  [Download this file](https://bootstrap.pypa.io/get-pip.py)
  In that folder, do `python get-pip.py`


settings.json for windows
```json
{
    "terminal.integrated.shell.windows": "C:\\WINDOWS\\System32\\cmd.exe",
    "workbench.iconTheme": "material-icon-theme",
    "explorer.confirmDragAndDrop": false,
    "explorer.confirmDelete": false,
    "files.autoSave": "onFocusChange",
    "editor.wordWrap": "on",
    "editor.rename.enablePreview": false,
    "workbench.editor.enablePreview": false,
    "window.zoomLevel": 0,
    "editor.suggestSelection": "first",
    "files.exclude": {
        "**/.classpath": true,
        "**/.project": true,
        "**/.settings": true,
        "**/.factorypath": true
    },
    "editor.tabSize": 2,
    "vsicons.dontShowNewVersionMessage": true,
    "python.languageServer": "Microsoft",
    "sshfs.configs": [
        {
            "host": "inside.sockettelecom.com",
            "name": "insidedev",
            "password": "Kr@IT9",
            "privateKeyPath": "c:\\Users\\administrator-yui\\.ssh\\id_rsa",
            "root": "/home/rkiew/dev",
            "username": "rkiew"
        }
    ],
    "php.validate.executablePath": "C:\\PHP",
    "workbench.startupEditor": "newUntitledFile",
    "[json]": {

        "editor.quickSuggestions": {
            "strings": true
        },
        "editor.suggest.insertMode": "replace"
    }
}
```
