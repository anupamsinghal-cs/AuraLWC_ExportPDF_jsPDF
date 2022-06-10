# Salesforce DX Project: Next Steps

Now that you’ve created a Salesforce DX project, what’s next? Here are some documentation resources to get you started.

## How Do You Plan to Deploy Your Changes?

Do you want to deploy a set of changes, or create a self-contained application? Choose a [development model](https://developer.salesforce.com/tools/vscode/en/user-guide/development-models).

## Configure Your Salesforce DX Project

The `sfdx-project.json` file contains useful configuration information for your project. See [Salesforce DX Project Configuration](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_ws_config.htm) in the _Salesforce DX Developer Guide_ for details about this file.

## Read All About It

- [Salesforce Extensions Documentation](https://developer.salesforce.com/tools/vscode/)
- [Salesforce CLI Setup Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_setup.meta/sfdx_setup/sfdx_setup_intro.htm)
- [Salesforce DX Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_intro.htm)
- [Salesforce CLI Command Reference](https://developer.salesforce.com/docs/atlas.en-us.sfdx_cli_reference.meta/sfdx_cli_reference/cli_reference.htm)

## About this project

I wanted to create ths project since there is minimal to none documentation on how to export Tables or 2 tables side by side from Aura component using pdfJS.
The only documentation I could find was exporting html tag tables to pdf using the html_to_pdf method in pdfJS
But in salesforce we rarely create our own table structures rather use the lightning:datatable to render perfect tables.

## Libraries used

- [pdfjs](https://unpkg.com/jspdf@2.5.1/dist/jspdf.es.min.js)
- [pdfjs-Autotable plugin for jspdf](https://unpkg.com/jspdf-autotable@3.5.25/dist/jspdf.plugin.autotable.js)