PTR image analysis example 2020115
Based on data from:
/media/daniel/202010/JData/B/B23/20210107/flyc3001

Install python3 dpkg
https://www.python.org/downloads/

In windows use python instead of python3. In linux and mac, use python3.

Run in the terminal:
python3 -m pip install pip --upgrade
python3 -m pip install pipenv

Make a folder to contain the python scripts and start the virtual environment.
Go to the folder in terminal.
Start virtual environment:
pipenv shell

Install the following packages:
pipenv install pandas
pipenv install numpy
pipenv install scikit-image
pipenv install scipy
pipenv install jupyterlab

The example tif file can be downloaded from here:
https://hhmionline-my.sharepoint.com/:i:/g/personal/busheyd_hhmi_org/EeeVuFKlRLROlYqo5fbsY1QBxl0u9UGusidqrpnyGmpH-w?e=6aN5sa


