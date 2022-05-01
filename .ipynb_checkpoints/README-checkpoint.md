# blockchain_ledger

A rudimentary streamlit application that uses blockchain to keep a ledger of transactions

---

## Technologies

This project uses Jupyter Lab in addition to the following libraries and add ons:

* [streamlit](https://docs.streamlit.io/library/get-started?msclkid=90f80fcec86511ec86357acd59d2b43a) for the user interface.

* [pandas](https://pandas.pydata.org/docs/) for working with dataframes.

* [haslib](https://docs.python.org/3/library/hashlib.html?msclkid=a7a6860bc86511ecb96f394a27d3543c) for hasing the blocks.

* [dataclasses](https://docs.python.org/3/library/dataclasses.html?msclkid=cee58621c86511ec8a5abaadba28fd0f) for classifying the data.

* [datetime](https://docs.python.org/3/library/datetime.html?msclkid=e396ee15c86511ec88b1f63bc0d726fc) for assigning dates in realtime.

---

## Installation Guide

Please run the following commands in your terminal before running the app:
```
pip install jupyterlab

pip install streamlit
```
---

## Usage

In order to use the application, run the comman '''streamlit run pychain.py''' in the terminal, this opens the homepage of the app:

![homepage](https://user-images.githubusercontent.com/96391748/166130015-084a9ffc-03af-48d9-8998-dfcb7f17e810.PNG)

In the application you create transactions that are saved in the ledger at the bottom:

![chain](https://user-images.githubusercontent.com/96391748/166130097-06286043-c5a9-4724-9516-60b96c6c01f6.PNG)

Finally, the user has the option to validate the chain:

![validation](https://user-images.githubusercontent.com/96391748/166130145-d70798c0-9b04-4f76-a0c3-ef4c9af043d1.PNG)

---

## Contributors

* Nicklaus Danialy nickdanialy@gmail.com 

---

## License

Copyright (c) [2021] [Nicklaus Danialy]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE