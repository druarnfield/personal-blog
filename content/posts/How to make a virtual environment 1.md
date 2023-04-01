---
title: Virtual Environments In Python
description: How to create and activate a virtual environment in Python
date: 2023-04-01
tldr: How to create and activate a virtual environment in Python
draft: false
tags: [python, virtualenv, virtual environment]
---


## Virtual Environment in Python

To create a virtual environment in Python, you can follow these steps:

1. Open a command prompt or terminal window.
2. Navigate to the directory where you want to create your virtual environment.
3. Enter the following command to create a new virtual environment:
```shell
python -m venv myenv
```
This will create a new virtual environment named myenv.

4. Activate the virtual environment. On Windows, run the following command:
`myenv\Scripts\activate.bat`
On macOS or Linux, run the following command:
```shell
source myenv/bin/activate
```

After running this command, you should see the name of your virtual environment in your command prompt or terminal prompt.

5. You can now install packages and run Python code within the virtual environment.

7. To exit the virtual environment, run the following command: `deactivate`

This will return you to your original command prompt or terminal window outside of the virtual environment.

That's it! You now know how to create and activate a virtual environment in Python.