# PyChain
You’re a fintech engineer who’s working at one of the five largest banks in the world. You were recently promoted to act as the lead developer on their decentralized finance team. Your task is to build a blockchain-based ledger system, complete with a user-friendly web interface. This ledger should allow partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.

## Tecnologies
Python
Streamlit
Dataclasses
Datetime
Pandas 
hashlib

## Instalation 

import streamlit as st
from dataclasses import dataclass
from typing import Any, List
import datetime as datetime
import pandas as pd
import hashlib

## Usage

Open the file pychain.py in your personal comuter, using the VS Code.

## Results

In this code we can see the follow outcome when we run the code by streamlit :
<img width="1606" alt="Screen Shot 2021-05-09 at 4 42 27 PM" src="https://user-images.githubusercontent.com/75823252/117590752-b2481580-b0e5-11eb-98bc-a43f2f767294.png">
 After that we can fill the sender and receiver to start add blocks to our blockchain:
 <img width="1575" alt="Screen Shot 2021-05-09 at 4 42 58 PM" src="https://user-images.githubusercontent.com/75823252/117590803-fc30fb80-b0e5-11eb-937d-f6373a584e82.png">
<img width="1603" alt="Screen Shot 2021-05-09 at 4 43 09 PM" src="https://user-images.githubusercontent.com/75823252/117590809-fe935580-b0e5-11eb-8c78-2cbd02fccffb.png">

After create our chain we can validate the chain:
<img width="1577" alt="Screen Shot 2021-05-09 at 4 45 11 PM" src="https://user-images.githubusercontent.com/75823252/117590825-17037000-b0e6-11eb-8f99-6d64cb2929e2.png">

We also are able to inspect the block chossing wich block we wanna check out:<img width="1521" alt="Screen Shot 2021-05-09 at 4 43 20 PM" src="https://user-images.githubusercontent.com/75823252/117590850-369a9880-b0e6-11eb-8be7-d66ca2bafb11.png">

## Contributors:
Matheus Araujo

## License 
Public
