# In staging
source my_project/bin/ (to activate local env)
deactivate (to exit local env)
pip freeze > requirements.txt (to install dependency info to requirements.txt file)

# In production
git clone ...
cd to project
pip install -r requirements.txt (install dependencies)
cd to src directory
python hello.py (run your project)
