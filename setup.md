### Set up Linux based system for this course
---

**Install Python3**
```bash
sudo apt install python3
```

Check if python is installed and working properly
```bash
python3 --version
```

**Install python3-venv to create virtual environments**

Virtual environment help us to isolate different working environments, we can install different set of libraries and/or different versions of same library for different project. 
```bash
sudo apt install python3-venv
```

Create one separate directory for this course

Virtual env, project files, course contents will be kept in this dir
```bash
mkdir AIAV
```

**Create virtual env(name: aiav_env) inside this dir**
```bash
python3 -m venv ~/AIAV/aiav_env
```

**Activate virtual env**
```bash
source ~/AIAV/aiav_env/bin/activate
```
If virtual env activated successfully, the name of virtual env will apper in brackets() before user name in terminal

**Install additional packages**

The packages installed after activating virtual env gets installed in venv so, it remains separate from base env or other virtual envs
```bash
pip install jupyter
pip install opencv-python
pip install open3d
```
> **jupyter** - web-based interactive computing platform

> **opencv-python** - most widely used Computer Vision library

> **open3d** - library that supports rapid development of software that deals with 3D data

**Deactivate virtual env**
```bash
deactivate
```
After deactivating virtual env, the name of env in brackets will disappear, we are back in default system env




