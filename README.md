# Project Overview
This Python bot interacts with dYdX v4 on Mainnet or Testnet to perform pairs trading.

## How It Works
It uses a z-score strategy to spot deviations from a moving average. When the z-score exceeds your chosen threshold, the bot places a trade on dYdX.

## Setup
1. Install Python 3.12.4 or higher.
2. Clone the repo and create a virtual environment:
   ```shell
   python3 -m venv venv
   pip3 install --upgrade pip
   source venv/bin/activate  # Windows users: venv\Scripts\activate
   ```
3. Install packages:
   ```shell
   pip3 install -r requirements.txt
   ```

## Configuration
Create a `.env` file in the `bot` folder, completing the details specified in `.env.examle`. 

## Run
```shell
cd bot
python main.py
```
