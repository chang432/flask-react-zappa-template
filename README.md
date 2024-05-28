# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
###### FLASK REACT ZAPPA TEMPLATE ######

1. Activate the venv: 'source venv/bin/activate' 
2. Pip install the python libraries: 'python -m pip install -r requirements.txt'
3. Prepare AWS credentials locally: 
- Run 'aws configure' and input your public and secret access key (Retreive from aws console)
- Make sure that profile is set as default: 'export AWS_PROFILE={PROFILE_NAME}'
4. Init zappa project: 'zappa init'