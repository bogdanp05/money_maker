# Backend

## Developing

1. Install Python 3.8 from the [official site](https://www.python.org/downloads/release/python-383/).

2. Install `virtualenv`, instructions [here](https://virtualenv.pypa.io/en/latest/installation.html). 

3. Create a virtual environment with `virtualenv` and activate it:
```shell script
virtualenv --python=python3 ENV
source ENV/bin/activate
```

4. Install requirements:
```shell script
pip install -r requirements
```

5. Set the line hard wrap in your editor at 79, as per PEP 8.

## How to run
```shell script
python demo_yfinance.py
```
