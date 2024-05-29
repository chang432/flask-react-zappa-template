###### PREREQUISITES ######
- Python 3.9
- AWS CLI
- AWS Account

###### FLASK REACT ZAPPA TEMPLATE ######

1. Create and activate the venv: 'python -m venv venv' + 'source venv/bin/activate' 
2. Pip install the python libraries: 'python -m pip install -r requirements.txt'
3. Prepare AWS credentials locally: 
- Run 'aws configure' and input your public and secret access key (Retreive from aws console)
- Make sure that profile is set as default: 'export AWS_PROFILE={PROFILE_NAME}'
7. In zappa_settings.json, replace {PROJECT_NAME} and {AWS_PROFILE_NAME} with the correct values
5. Cd into frontend/ and then run 'npm ci'
6. Run 'npm run dev' and make sure the website is reachable
7. Go back to the root of the project and run 'bash local_deploy.sh' to test if the flask application is working
8. Initialize the zappa dev application with 'zappa deploy dev'
9. Then in deploy_dev.sh and scripts/upload_static.py, replace {BUCKET_NAME} with your dev bucket name and run 'bash deploy_dev.sh'