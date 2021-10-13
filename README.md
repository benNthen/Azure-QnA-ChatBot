# Azure-QnA-ChatBot
A simple webpage that contains a chatbot that answers the questions based on the [Turners' FAQ about Online Auctions page](https://www.turners.co.nz/Cars/how-to-buy/Online-auctions/). This uses Microsoft Azure Web App Bot Services and QnA Maker API to provide a response to the queries entered by the user.

## Using the repository
After downloading, simply open the `index.html` file.

## How To Use:
-----------

The bot will return the answers based the questions listed inside the `TurnersAuctionFAQ.docx` which had been uploaded into the QnA Maker API.

![image](https://user-images.githubusercontent.com/53241776/137051800-6f548d31-7c0e-4cab-8f6e-43dbb811eab4.png)
Figure 1: Shows a preview of the chatbot answering queries made by the user based on the Turners' Cars FAQ.

The list of all possible questions to ask are listed below:

- How can I bid on Turners Online Auctions?
- Why do I need to link my Turners account to Trade Me?
- What if I don’t link my Turners account to Trade Me?
- What if I don’t have a Trade Me account?
- What’s the difference between online auctions and Turners live?
- What’s an autobid?
- How do I place an autobid?
- What’s a screen name?
- What payment options are there?
- Are there any buyers fees?
- What shipping options are there?
- How do I ask a question about a good?
- Why am I receiving emails from Trade Me?
- How do I apply for finance?

## How It Works
-----------
The chatbot was created using Microsoft Azure's Web App Bot Services to create the bot itself. The QnA Maker API is implemented on the bot in order to customize the answers that it provides. Additional questions and answerse were given on the QnA Maker.

![image](https://user-images.githubusercontent.com/53241776/137053462-9635e681-1981-4367-b70b-76c536690ffa.png)
Figure 2: A portion of the QnA Maker API window that shows how a question and its corresponding answer are being added.
