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
4. Init zappa project: 'zappa init'