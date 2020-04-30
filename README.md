# recommended-extensions-poc

View the extensions that project collaborators will be prompted to install when the workspace opens in .vscode/extensions.json

An extension is identified using its publisher name and extension identifier publisher.extension. You can see the name on the extension's detail page. VS Code will provide you with auto-completion for installed extensions inside these files.
![](https://code.visualstudio.com/assets/updates/1_6/extension-identifier.png)

An extension named example-extension by the author example-author can be added to the recommended extensions like so:
    
    // This file is .vscode/extensions.json

    {
        "recommendations": [
            "stepsize.tech-debt-tracker",
            "streetsidesoftware.code-spell-checker",
            "wix.vscode-import-cost",
            "example-publisher.example-extension"
        ]
    }