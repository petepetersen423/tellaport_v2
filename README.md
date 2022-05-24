# *Tellaporte*

### By: Pete Petersen and Dakota Braxton

        March 27, 2022  
---
**Welcome to the ETF Analyzer Project we call Tellaporte!**

This project was a collaborative effort between two sutdents enrolled in the Pepperdine Bootcamp.  We were charged with developing a fintech application using some of the techniques we leaned in the previous 8 weeks.  Telleporte is the result

# Project Deliverables  

[Tellaporte Project Website](https://tellaporte.godaddysites.com/)  

[Tellaporte Pitch Deck](https://docs.google.com/presentation/d/1tjTHTjb50yCuq5buGgM85Py6MKm5J6Bn/edit#slide=id.g11a97544c2e_1_11)  

# Background

Tellaporte is a financial wellness application for the community of Nurses. We have chosen Nurses because they are a brilliant and dedicated group of people that give selflessly of themselves almost every day. Because nurses care more for others than themselves and are continuously challenged with life and death every day, they often neglect their health and the health of their retirement. In a nurse's mind, money does not matter relative to the demands of their job and the needs of their patients. With this in mind, we wrote Tellaporte to aid the nurses in financial wellness by simply building an application that speaks the language of nurses so that they can easily understand and correlate their financial wellness in the terminology they already know. Nurses are there for our wellness. Now Tellaporte is there for their financial wellness.

![Tellaporte](Tellaporte.jpg)

## Dependencies

To begin the project you must clone this repo and install the following dependincies:

```python

import quandl
import logging
from pathlib import Path
import zipfile
import pandas as pd
import os.path
from dotenv import load_dotenv


```

The /data directory contains all the parquet files needed for the analysis so you do not need to get API keys.  However if you have keys and the files do not exist the app will generate new data.

## Files

    ETF.ipynb
    /data/
        etf_const
        financial_ind
        mer
        prices
        tech_ind
        zacks

# Tellaport Version 2

This is the second submittal of the Telaport application and focuses on voice bot and chatbot integrations as simple interface for the nurses to interact with.

The repo contains the lambda code, the mobies of the chatbit, and the voice recording of a live phone call.

## Technologies

Amazon Connect
Amazon Lex
Amazon Lambda
Amazon Contact Flow
Amazon Polli
Amazon IAMS
