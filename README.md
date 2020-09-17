# Backup Bot

A bot that counts the number of messages per user and per channel in a Discord server.

#### Instructions
1. Create `.env` with the details specified in `example.env`
2. Run the following commands to setup the environment:
```bash
virtualenv .venv
source .venv/bin/activate
pip install -r requirements.txt
```
3. Run the bot using `python -m backup --stats` or `python -m backup --backup` 
4. Results will be in the files `channel_stats.csv` & `user_stats.csv`
