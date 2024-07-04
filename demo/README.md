# SpeechTone-Erie: A Demo Project

## How to Run the Project

To run this project, execute the following command with Python 3:

```
python -m http.server 8080
```

This command starts a local server and hosts the webpage. Hosting the webpage is necessary for dynamically loading local files.

We recommend accessing the URL `localhost:8080` using a Chromium-based browser, such as Google Chrome or Microsoft Edge. This is because different platforms offer varying lists of speech voices through the Web Speech API. Please note that for Demo 3, if you use a browser other than Chrome or Edge, the voices may not match the descriptions provided in the paper. 

Once the server is up and running, you can interact with the demo. Click on the demo buttons to listen to three different speech sonifications which correspond to the descriptions provided in the accompanying paper.

## Understanding the Folder Structure

The 'erie-web.js' file is a key component of this project. It is built from the source project "SpeechTone-Erie-Source" and extends the original Erie library to include SpeechTone.

The 'index.html' file is another crucial part of the project. It uses JavaScript to read the dataset from the `/data` directory and specifications from the `/specs` directory. Using these inputs, it constructs the speech sonification with the extended Erie library with SpeechTone.