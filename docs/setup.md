---
id: setup
title: Setting Up
---

### Getting Started

First of all, clone the following repository in order to access the databse:

```js
git clone 'git@github.com:calopessoa/log-quake.git'
```
Then, move to the backend folder and install dependencies

```js
cd log-quake
```

This project was parsed using Python. Make sure to use Python. In order to run the tests, it is important to be in a isolated environment, let's use Venv

:::tip
In case it is necessary, go to Python official download page and select your Operational System(OS): https://www.python.org/downloads/

_This guide will presume the user is using a Linux distro_

_If venv is not installed, run this command: **sudo apt install python3-venv**_
:::

Activate Venv
```js
source .venv/bin/activate
```

Install testing dependencies
```js
python3 -m pip install pytest
```
<!-- You should get this response:
![Example banner](../static/img/buildrunning.png) -->

