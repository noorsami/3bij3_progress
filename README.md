# 3bij3_progress
Progress of running 3bij3 Framework on local

# Step 1: Create virtual env
```
python3 -m venv venv
```
# Step 2: Activate venv
```
source venv/bin/activate
```
# Step 3: Install requirements
```
pip install -r requirements.txt
```
# Step 4: Processing file + pkls
- Place the file extras/driebijdrie_processing.py in the venv/lib/inca package under venv/lib/python3.7/site-packages/inca/processing/
- Place de pkls I sent through WeTransfer in de base directory of inca --> venv/lib/python3.7/site-packages/inca/

# Step 5: Database settings
I changed up the database settings to postgres. In the config file you will still see my settings. For me it would not be a problem to still keep using mysql if it works or another db
