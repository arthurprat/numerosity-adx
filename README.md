# How to

2025/12/28

## 1. Make a virtual environment

(If you don't have one already.)  
Go to the repository you want the project to be in and run:

`python -m venv env`

## 2. Activate the virtual environment

`. ./env/bin/activate`

## 3. Install psychopy and exptools2

```
pip install psychopy
pip install git+https://github.com/Gilles86/exptools2/
```

## 4. Clone this git repo

`git clone https://github.com/arthurprat/numerosity-adx.git`

## 5. Run an experiment

Go to the experiment repo:

`cd experiment`

Run the experiment for subject 01, session 1, with the narrow range, outisde the scanner:

`python run_noscanner_onerange.py 01 1 narrow`

