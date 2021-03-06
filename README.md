Medibot
=======

Medibot is a bot for searching Hospital and Doctor information in Indonesia
Powered by [Microsoft BotFramework](https://dev.botframework.com/)
- telegram: [@idMedibot](https://telegram.me/idMedibot)
- skype: [![](https://dev.botframework.com/Client/Images/Add-To-Skype-Buttons.png)](https://join.skype.com/bot/980d10e3-6c9b-4ec6-b89d-0bd5c30e0288)
- facebook: @Medibotid (waiting for review)

## Tools You Need ##
- [NodeJS](https://nodejs.org/en/)
- [Bot Emulator](https://docs.botframework.com/en-us/tools/bot-framework-emulator/)(Windows Only)
- [Visual Studio Code](https://code.visualstudio.com)

## Installation ##

    npm -install

## Debugging Locally ##
By Using Visual Studio Code, you can press **F5** to start debugging your application.
This git does not provide *.vscode* folder, but when you start hitting the **F5**, VSCode will automatically create *.vscode* folder with *launch.json* file included. please ensure the start point of your apps is app.js

    ...
        "configurations": [
            {
                "name": "Launch",
                "type": "node",
                "request": "launch",
                "program": "${workspaceRoot}/app.js",
    ...

after the program started, you can use [Bot Emulator](https://docs.botframework.com/en-us/tools/bot-framework-emulator/) to test the program
don't forget to type your own Bot's Credential

## Debugging using ngrok ##
to be added...

## Glossary ##
- app.js: start point of the application
- bot.js: contain all codes about bot
- hub.js: the service layer, bridging the data layer to presentation layer
- connector: middle layer between service and data layer, this layer providing data to data layer by crawling some websites
- dataStorage.js: data layer 

## Programmer's Note ##
- If you have some spare time and want contribute in this project, just fork this git and make a pull request
- Any contribution, either small or big are really appreciated
- Medibot is licensed under WTFPL, so just **Do What the Fuck You Want To** with this sourcecode
 
## Roadmap ##
- scrapping doctors information from current listed hospital 
- adding more hospital information
- connecting the application to proper database

![WTFPL](http://www.wtfpl.net/wp-content/uploads/2012/12/wtfpl-badge-4.png)
