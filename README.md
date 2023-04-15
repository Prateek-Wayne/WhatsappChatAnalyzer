# WhatsappChatAnalyzer
This is a simple WhatsApp chat analyzer web application built with Python Flask framework. It allows users to upload their exported WhatsApp chat history and generates various statistics and visualizations. It uses the Pandas and Matplotlib libraries to process and visualize the data.

##Installation
To install the dependencies, run the following command:
* pip install -r requirements.txt

Usage
To start the web application, run the following command:
* python app.py

This will start the web application on your local machine at http://127.0.0.1:5000/.

To analyze your WhatsApp chat history, follow the below steps:
- Export your WhatsApp chat history from your phone
- Click on the "Choose File" button and select the exported chat file
- Click on the "Upload" button
- Wait for the analysis to complete
- The analysis results will be displayed on the web page, including various statistics and visualizations

## Features
- Total number of messages sent and received by each participant
- Total number of media messages sent and received by each participant
- Total number of words and characters sent by each participant
- Hourly and daily chat activity
- Wordclouds for each participant's most frequent words
- Heatmap of chat activity over the week

Export your WhatsApp chat history from your phone
Copy the exported chat file to the same directory as whatsapp_chat_analyzer.py
Rename the chat file to chat.txt
Run the script using the following command:
* python whatsapp_chat_analyzer.py

This will generate a set of output files in the output directory, including stats.txt and various visualizations.

### Contributing
Contributions are always welcome! Please follow the below steps to contribute:

- Fork the repository
- Create a new branch (git checkout -b new-feature)
- Make changes and commit (git commit -am "Added a new feature")
- Push to the branch (git push origin new-feature)
- Create a pull request
- License
- This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements
- Pandas library
- Matplotlib library
- Wordcloud library
