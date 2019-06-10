# Flask Blog
Blog website using Flask 



# Running the Application 

git clone https://github.com/SuneharSandhu/Flask-Blog-.git

cd Flask\ Blog/

source env/bin/activate

pip install -r requirements.txt

Now change the config.py file:

From:

MAIL_USERNAME = os.environ.get('EMAIL_USER')
MAIL_PASSWORD = os.environ.get('EMAIL_PASS') 

To:

MAIL_USERNAME = 'your_email_address@gmail.com'
MAIL_PASSWORD = 'your_password'

This will allow the website to access your gmail for password resets

If you use this code on a production sever replace the DEBUG variable with False.

Now to run the application, enter the following command:

python run.py or python3 run.py



