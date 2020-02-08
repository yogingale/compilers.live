# compilers.team
Portfolio website running as Flask app

Prod - https://yogesh-portfolio.herokuapp.com/

Stage - https://yogesh-portfolio-stage.herokuapp.com/


## Setup

Create and Enable python virtual environment.
`python -m venv venv`
`source venv/Scripts/activate` - For Windows
`source venv/bin/activate` - For Mac

Install Python dependencies
`pip install -r requirements-dev.txt`

Run the following to update then refresh your .bashrc:  
echo "source `which activate.sh`" >> ~/.bashrc  
source ~/.bashrc  
Now, if you move up a directory and then cd back into it, the virtual environment will automatically be started and the APP_SETTINGS variable is declared.  

## How to start the project?
Run below command once you are done with all the steps from [Setup](#setup)  
`python app.py`  
Open the site on browser at http://127.0.0.1:5000/  

## Extra
To setup email configuration for contact us form. 
add below environment variables-  
EMAIL_USER=<email-address>
EMAIL_PASSWORD=<email-app-password>