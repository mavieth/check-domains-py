# Check Domain Availability in Python

## Install Virtualenv
```python
sudo pip install virtualenv
```

## Clone Project
```bash
git clone https://github.com/mavieth/check-domains-py.git
cd check-domains-py
virtualenv venv
source venv/bin/activate

pip install pythonwhois
```
## Add domains to domains.txt
Add domains (one per each line) for checker to check. It will print out availability.

## Run Script
```python
python check.py
```






