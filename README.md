Flask Stripe Example
====================

Launch
--------------------
1. `cd stripe_test`
2. `python -m venv venv`
3. `. venv/bin/activate`
    > btw you are free to use the python enviroment utility of your choice
4. `pip install -r requiroments.txt`
5. next you need to register a test app at the stripe.com
6. add STRIPE_SECRET_KEY and STRIPE_WEBHOOK_SECRET to your local enviroment. Take the values from your stripe test app dashboard
7. `flask run`
8. ngrok http [port] 
> For some time your app will be accesable from the web via public link (true magic)


based on
> https://github.com/miguelgrinberg/flask-stripe-orders