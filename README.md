## install/run

    pipenv install
    pipenv run python pingstats.py

## usage

Ping google for an hour:

    pipenv run python pingstats.py --host google.com --comment 'pinging google for 1 hour' --ping_amount 86400
    
Ping 8.8.8.8 for 2 weeks:

    pipenv run python pingstats.py --host 8.8.8.8 --comment 'pinging 8.8.8.8 for 1 week' --ping_amount 604800
