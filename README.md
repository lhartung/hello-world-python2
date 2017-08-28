Hello world chute written with Python v2
===================================================
This simple chute demonstrates the basic structure required to build a chute with Python.

Testing on your development machine
-----------------------------------

```
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt
python -m helloworld.server -p 5000
```

Deploying to Paradrop
---------------------

```
pdtools device --address=<router_ip> chutes install
```
