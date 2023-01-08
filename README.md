 <h1 align="center">Test task for LeadHit</h1>
 
 ## Requirements

- [Pip == 22.3.1](https://pypi.org/project/pip/)
- [Python >= 3.10](https://www.python.org/downloads/release/python-3100/)

 ## Local development in Ubuntu v.20.04
 
Clone the project to the directory we need:

```shell
git clone https://github.com/Fischer0007/test_task_for_leadhit.git
```

Installing requerements for python:

```shell
pip install -r req.txt
```

Run app:

```shell
python3 api/app.py
```

Run tests for application with full report:

```shell
python3 -m pytest -rqpP api/tests/test_main.py
```
