# Prep

## Node.js


Here are the instructions to get an echo bot that maintains state across conversation turns to count the number of messages the user sends:

- Clone the BotBuilder-Samples repository in github
    ```bash
    git clone https://github.com/microsoft/botbuilder-samples.git
    ```
- In a terminal, navigate to `samples/javascript_nodejs/02.echo-bot`
    ```bash
    cd samples/javascript_nodejs/02.echo-bot
    ```
- Install modules
    ```bash
    npm install
    ```
- Start the bot
    ```bash
    npm start
    ```

You will also find a wealth of samples under samples/javascript_nodejs. Each sample bot has a thorough readme with instructions on how to run it. We recommend using 02.echo-bot for text based bots and 06.using-cards for bots that send images, videos or audio. 

To talk to your bot, see the section below on how to use the Bot Framework Emulator.

## C#

Here are the instructions to get an echo bot that maintains state across conversation turns to count the number of messages the user sends:

- Clone the BotBuilder-Samples repository in github
    ```bash
    git clone https://github.com/microsoft/botbuilder-samples.git
    ```
- Navigate to the samples folder (`botbuilder-samples/samples/csharp_dotnetcore/02.echo-bot`) 
- Open readme.md to see the instructions to run the bot using either Visual Studio or Visual Studio code.

You will also find a wealth of samples under samples/csharp_dotnetcore. Each sample bot has a thorough readme with instructions on how to run it. We recommend using 02.echo-bot for text based bots and 06.using-cards for bots that send images, videos or audio. 

# Try your bot using Bot Emulator

[Microsoft Bot Framework Emulator](https://docs.microsoft.com/en-us/azure/bot-service/bot-service-debug-emulator?view=azure-bot-service-4.0) is a desktop application that allows bot developers to test and debug their bots on localhost or running remotely through a tunnel.

- Install the Bot Framework Emulator from [here](https://github.com/Microsoft/BotFramework-Emulator/releases).

## Connect to the bot using Bot Framework Emulator **v4**
- Launch Bot Framework Emulator
- File -> Open Bot 
- Enter the local url for your bot. For all samples the default url is http://localhost:3978/api/messages.

# Bot Resources

* [Bot Framework Documentation](https://docs.microsoft.com/en-us/azure/bot-service/?view=azure-bot-service-4.0)
* [Github: Bot Framework Samples: C# and Node.js](https://github.com/Microsoft/BotBuilder-Samples)
* [Github: Bot Framework C# source code](https://github.com/Microsoft/botbuilder-dotnet)
* [Github: Bot Framework Node.js source code](https://github.com/Microsoft/botbuilder-js)
* [LUIS for Language Understanding](https://www.luis.ai/)
* [Cognitive Services](https://azure.microsoft.com/en-us/services/cognitive-services/)
