# Installation

## Upgrade pip
```bash
$ python -m pip install --upgrade pip
```


```bash
$ python -m pip install virtualenv
$ virtualenv venv
$ source venv/bin/activate
$ python -m pip install --upgrade pip
```

## Install gRPC

```bash
$ python -m pip install grpcio
$ python -m pip install grpcio-tools
```

## Save the dependencies

```bash
$ pip freeze > requirements.txt
```