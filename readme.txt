Instruction for VSCode Editor User

1. Select Project folder and open in VSCode Editor

2. Open New Terminal

Create Virtual Environment for run Python.
	python -m venv venv (hit Enter on keyboard)
	# you get a prompt down-right side of the vscode editor
	# We noticed a new environment has been created. Do you want to select it for the workspace folder
	# click on Yes button.


Set Execution Policy
	Set-ExecutionPolicy -Scope Process -ExecutionPolicy RemoteSigned (hit Enter on keyboard)

Activate Virtual Environment
	.\venv\Scripts\Activate (hit Enter on keyboard)
	# after this command you can see in terminal (venv) is in green color, means it activated.

Install Required Packages
	pip install -r requirements.txt