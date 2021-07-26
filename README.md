# Blockchain Based Ledger Application


<img width="556" alt="Screen Shot 2021-07-26 at 12 14 27 PM" src="https://user-images.githubusercontent.com/80833988/127045555-ce8f3ba1-63d6-4e37-9597-c1f4decbe26d.png">


📌 Challenge 18

> "In this Challenge, I assumed the role of a financial engineer. I am building a Blockchain Based Ledger Application with user-frienly intrface on a streamlit to conduct simple value transfer and verify integrity of the transaction "


## Table of content
- [Overview of the project and project goals]() 
- [Project steps]()
- [Software version control](https://github.com/nataliaburrey/Machine_Learning_Trading_Bot/blob/main/README.md#software-version-control)
    - [Libraries](https://github.com/nataliaburrey/Machine_Learning_Trading_Bot/blob/main/README.md#libraries)
    - [Work with GitHub](https://github.com/nataliaburrey/Machine_Learning_Trading_Bot/blob/main/README.md#work-with-github)
    - [How to install](https://github.com/nataliaburrey/Machine_Learning_Trading_Bot/blob/main/README.md#how-to-install)
- [Helps recruiters](https://github.com/nataliaburrey/Machine_Learning_Trading_Bot/blob/main/README.md#helps-recruiters)
- [License](https://github.com/nataliaburrey/Machine_Learning_Trading_Bot/blob/main/README.md#license)



## Overview of the project and project goals

The task is to build a blockchain-based ledger system, complete with a user-friendly web interface. 
This ledger should allow partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.
 
## Project steps

The steps for this Challenge are divided into the following sections:

### 1. Create a Record Data Class

[
<img width="599" alt="Screen Shot 2021-07-26 at 11 57 40 AM" src="https://user-images.githubusercontent.com/80833988/127043560-b2140ca4-a0df-4862-8595-677ebc566b53.png">
](url)

### 2. Modify the Existing Block Data Class to Store Record Data

<img width="618" alt="Screen Shot 2021-07-26 at 11 58 20 AM" src="https://user-images.githubusercontent.com/80833988/127043650-be43db94-edd6-4785-b341-5dd88de113ff.png">


### 3. Add Relevant User Inputs to the Streamlit Interface

<img width="623" alt="Screen Shot 2021-07-26 at 12 07 52 PM" src="https://user-images.githubusercontent.com/80833988/127044765-5f2572b1-e860-4d02-a90a-e53c9c69d8b3.png">


### 4. Test the PyChain Ledger by Storing Records

##### Screenshot of a sidebar 

<img width="320" alt="Screen Shot 2021-07-26 at 11 39 52 AM" src="https://user-images.githubusercontent.com/80833988/127044790-195b0f68-94bd-4c00-a07e-d3e7c17356be.png">

##### Interaction with a blockchain


https://user-images.githubusercontent.com/80833988/127045133-617e4da6-f4ae-415b-95ed-ec1b3f4ffc0f.mov

![Uploading Screen Shot 2021-07-26 at 12.13.59 PM.png…]()


## Software version control


### Libraries 
*  Pandas - is a software library designed for data analytics that makes it easier to work with data from practically any type of file. Pandas supplies powerful tools for working with time data in particular, and time is a key aspect of financial analysis. Analysts typically compare and measure financial assets—from single stocks to large portfolios—across time.
* Streamlit- is an open-source app framework for Machine Learning and Data Science teams.
* Dataclasses-a utility tool to make structured classes specially for storing data. These classes hold certain properties and functions to deal specifically with the data and its representation.
* Typing-provides runtime support for type hints. The most fundamental support consists of the types Any, Union, Tuple, Callable, TypeVar, and Generic.
* Datetime-supplies classes for manipulating dates and times.
* Hashlib-Python hashlib hashing function takes variable length of bytes and converts it into a fixed length sequence. This is a one way function. 



##### Following libraries were imported

```
# Import the required libraries and dependencies

import streamlit as st
from dataclasses import dataclass
from typing import Any, List
import datetime as datetime
import pandas as pd
import hashlib

```


 
### Work with GitHub
* Repository created on GitHub
* Files were  committed using command line
* Our repository is organized, and includes Resources folder with CSV  project files, 
* Jupyter Notebook with code runs without errors.
* Answers on nesassary questions are included

### How to install

* Save remote repo from GitHub to your computer (Desktop): in Terninal type:

```
cd desktop

git clone https://github.com/nataliaburrey/Machine_Learning_Trading_Bot.git
```

now you can find repo on your desktop


* Choose [ machine_learning_trading_bot.ipynb ] file to see the Jupyter Notebook with code.




## Helps recruiters

The project was created in collaboration with Berkeley Fintech Bootcamp team


## License

[MIT]()

📔 Contact me: 
📩 nataliaburrey@gmail.com
