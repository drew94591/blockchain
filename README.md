# Blockchain Ledger
This application implements a blockchain-based ledger system which mimics how a bank records financial transactions such as money transfers between senders and receivers using a blockchain.  The application also verifies the integrity of the data within the ledger.

---

## Technologies

This application leverages python 3.7 with the following libraries and packages:

* [streamlit](https://streamlit.io) - An open-source app python framework that turns data scripts into shareable web apps in minutes.

* [dataclasses](https://docs.python.org/3/library/dataclasses.html) - A module that provides a decorator and functions for automatically adding generated special methods to user-defined classes.

* [typing](https://docs.python.org/3/library/typing.html) - A module which provides runtime support for type hints.

* [datetime](https://docs.python.org/3/library/datetime.html) - A module which supplies classes for manipulating dates and times.

* [pandas](https://github.com/pandas-dev/pandas) - A flexible and power data analysis/manipulation Python library used in financial calculations.

* [hashlib](https://docs.python.org/3/library/hashlib.html) - A module which implements a common interface to many different secure hash and message digest algorithms.

---

## Installation Guide

Before running the application first install the following dependencies.

### Python Modules
```python
  $ pip install streamlit
```

---

## Usage

To use the Blockchain Ledger application you must first launch Streamlit by executing the following command within Git Bash:

```python
streamlit run pychain.py
```

As is illustrated below:

![Blockchain Ledger](pychain_ledger.gif)


---

## Contributors

Brought to you by [Drew Herrera](https://www.linkedin.com/in/andrewjherrera).

---

## License

Licensed under the MIT License. Copyright 2022 Drew Herrera.
