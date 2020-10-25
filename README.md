# Video

[How to use[RUS]](https://youtu.be/RWVld4OqsM0)

# Why

<cite>
Virtual environments are already widely used for dependency management and isolation, ease of installing and using Python packages without system-administrator access, and automated testing of Python software across multiple Python versions, among other uses.
</cite>

[PEP 405 -- Python Virtual Environments](https://www.python.org/dev/peps/pep-0405/)

[venv — Creation of virtual environments](https://docs.python.org/3/library/venv.html?highlight=venv#module-venv)

## Why example

### Project's 1 deps
 \# flask project

```bash
pip freeze
click==7.1.2
Flask==1.1.2
itsdangerous==1.1.0
Jinja2==2.11.2
MarkupSafe==1.1.1
Werkzeug==1.0.1
```
------------------
### Project's 2 deps
 \# Django project

```bash
pip freeze
asgiref==3.2.10
Django==3.1.2
pytz==2020.1
sqlparse==0.4.1
```

**How to manage them?**

## Create Virtual Environment!

### How?

Available sinse python 3.3 as a buildin module

```bash
# linux
python3 -m venv env

# venv - module name
# env - Virtual Environments folder name (and path to it), just env means create it in current folder
```

```bash
# win cmd
python -m venv env

# venv - module name
# env - Virtual Environment's folder name (and path to it), just env means create it in current folder
```

## Activate Virtual Environment!

```bash
# linux 
source ./env/bin/activate

# ./env/bin/activate - run activate script. Folder env is in the cuttent folder
```

```ps
# win cmd 
.\env\Scripts\activate

# .\env\Scripts\activate - run activate script. Folder env is in the cuttent folder
```
If everything is ok you should (env) at the beginning of your promt


## Deactivate Virtual Environment!

```bash
# linux win
deactivate
```
