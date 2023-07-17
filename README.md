# Mod18Chall
This is a project in which I create a crude version of a block chain and deploy it on a [streamlit](https://github.com/streamlit/streamlit) application.

## Technologies
The following packages were used:
pandas
hashlib
datetime
typing
dataclasses
streamlit

## Installation
Of the packages utilized, everything should come preinstalled into python 3.7 except for streamlit.
To install streamlit, in your terminal run:

`pip install streamlit` and follow any direction prompts.


## Usage

### Code
Code is found in [pychain.py](https://github.com/wcolwellcol/Mod18Chall/blob/main/Starter_Code/pychain.py) within the starter_code folder. Note, the embedded streamlit commands (denoted by `st.[something]`) which enables deployment. 

### Run the App
With your terminal, navigate to the folder that holds the pychain.py app. Run the script in the terminal with the command `streamlit run pychain.py`

A page should automatically open in your web browser where the app is deployed.

Enter info in the text info fields for sender, receiver, and amount.
Click 'add block' and scroll down to the ledger to verify that your block has been added.
You can even validate the chain by clicking the 'Validate Chain' button.

Your screen should look something like this (![Screenshot of app](<Screenshot 2023-07-11 at 4.12.59 PM.png>))
