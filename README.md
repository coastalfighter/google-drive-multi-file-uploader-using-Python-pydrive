## google-drive-multi-file-uploader-using-Python-pydrive
=>Simple script to upload multiple files on Google Drive by converting them into .zip file.

## Description
=>Script uses predefined [Drive APIs Client ID and Client Secret].

=>It takes upload file as command line argument, uploads it and sets permissions that anyone who has download link can download the file.

## Requirements
=>Python 2.7.4

=>pydrive(http://pythonhosted.org/PyDrive/quickstart.html) use this link for reference.

=>[google-api-python-client](http://code.google.com/p/google-api-python-client/)

## Configuration
=>use the link (https://console.developers.google.com/start/api?id=drive) to generate **client ID** and **client secret** strings (download `client_secret.json`). Choose **other** for **application type**.

=>save the `client_secret.json` and `multi-file_uploader.py` in the same folder.

## Procedure
=>Open the command prompt

=>Navigate to the folder path

=>Run the program (python multi-file_uploader.py)

=>Provide the folder path that has to be zipped and uploaded.

# Note:
=>This project is done under the guidance of Zaid Sir and Digipodium(www.digipodium.com)

=> Made by Gaurang Shukla(grngshukla@gmail.com)
