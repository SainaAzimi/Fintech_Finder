# **Fintech Finder**
A web-based marketplace to find fintech professional candidates, hire them, and pay their wages on the blockchain using Ether.

---

## Technologies
This application is developed on the *Python 3.7.11 version*:


* [streamlit](https://docs.streamlit.io/library/get-started?msclkid=90f80fcec86511ec86357acd59d2b43a) for the user interface.

* [pandas](https://pandas.pydata.org/docs/) for working with dataframes.

* [hashlib](https://docs.python.org/3/library/hashlib.html?msclkid=a7a6860bc86511ecb96f394a27d3543c) for hasing the blocks.

* [dataclasses](https://docs.python.org/3/library/dataclasses.html?msclkid=cee58621c86511ec8a5abaadba28fd0f) for classifying the data.

* [datetime](https://docs.python.org/3/library/datetime.html?msclkid=e396ee15c86511ec88b1f63bc0d726fc) for assigning dates in realtime.

* [web3](https://web3js.readthedocs.io/en/v1.7.3/) to work with the ethereum blockchain.

---

## Installation Guide
Before running the application first install the following:
```
- pip install streamlit  

- pip install jupyterlab
```

---

## Usage
First, in order to use the application, run the comman '''streamlit run fintech_finder.py''' in the terminal, this opens the homepage of the app including a list of available professionals.
Next, in the sidebar of the application you have the option to select one of the professionals and select an amount of time to hire them for.
Finally, the user clicks the "Send Transaction" button at the bottom of the sidebar which sends the transaction to the ethereum account.
As a result, the cost of the transaction is taken out of your account which is reflected in the ganache software under the accounts tab.
Lastly,the transactions are saved on the ganache application under the "Transactions" tab.


---

## Contributors

*Contributors*: Saina Azimi

*Email*: azimi.sainaa@gmail.com

*LinkedIn*: https://www.linkedin.com/in/azimi-saina/ 

---

## License
UC Berkeley

---