# ORDER SERVICE

### This is a microservice, part of CoffeMash project

## Steps: [setup environment locally]

### 1. Clone repo

```
git clone https://github.com/CodeForTravel/micro_order.git
```

### 3. Create environment and activate

```
python3 -m venv env
source env/bin/activate
```

### 4. Install dependencies for project

```
pip install -r requirements.txt
```

## Go to project directory and run the below command

```
export PYTHONPATH=$PWD
```

## Run the server

```
uvicorn orders.app:app --reload
```
