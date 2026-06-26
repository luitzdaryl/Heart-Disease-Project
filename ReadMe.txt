1- Create a virtual environment (venv) in your project folder:
python -m venv env

Or with a specific version

py -3.11 -m venv env

2- Activate it:
env\Scripts\activate

3- Install packages:
pip install jupyter pandas numpy matplotlib scikit-learn seaborn

4- Install ipykernel
pip install ipykernel

Option 1: From the terminal where Jupyter is running
When you launch Jupyter via:

jupyter notebook
or
jupyter lab

Need to choose python environment

it prints something like this in the terminal:
   To access the notebook, open this file in a browser:
        file:///Users/user/...
    Or copy and paste one of these URLs:
        http://localhost:8889/?token=abcd1234efgh5678

Copy the URL with the ?token=... part.
 That’s your full token URL.