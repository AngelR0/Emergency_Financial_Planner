# Emergency & Retirement Financial Planner
![Emergency](https://princewilliamlivingweb.s3-accelerate.amazonaws.com/2022/01/shutterstock_1025314012-scaled.jpg)
## Description

The first half of the application is a tool to visualize the members current savings, then determine if they have any reserves left for an emergency fund. 

The second half of the application is a tool forecasts the performance of the members retirement portfolio in 30 years and 10 years.

* To make this happen we will make an Alpaca API call.
* Then run a Monte Carlo simulation to forecast both 30 and 10 years plan.
----------------------------------------------------------------
## Installations
Runs on Python 3.7. First we need to confirm that we have the **Requests** and **JSON** libraries were installed with **Anaconda**. 

As well to call the .env file we need to install **Python-dotenv Library**. 

To call the **Alpaca API** we need to install **Alpaca SDK**

--- 
## How to install
* **Requests**: 
  ```python 
  conda install -c anaconda requests 
  ```
* **JSON**:
  ```python
  conda install -c jmcmurray json
  ```
* **Python-dotenv**:
  ```python
  pip install python-dotenv
  ```
* **Alpaca SDK**:
  ```python
  pip install alpaca-trade-api
  ```

---
## Running the Application
To run the application successfully, you will need to acquire an [Alpaca API Key](https://app.alpaca.markets/signup) and [Alpaca Secret Key](https://app.alpaca.markets/signup) (Click on either links to get your keys).


    
---
## Contributors
Brought to you by Angel Reyes