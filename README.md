# Flask Blog
Blog website using Flask 

<img width="1440" alt="Screen Shot 2019-06-09 at 10 25 28 PM" src="https://user-images.githubusercontent.com/16765940/59169146-fb147f80-8b06-11e9-9404-7f6d906d4f70.png">


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



