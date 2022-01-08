Flask Stripe Example
====================

This app represents Flask Stripe integration example. There are two products in the app. You can purchase and see payments info into your Stripe dashboard. To test the payment proccess use test payment creds:
card number 4242 4242 4242 4242 will always succeed and 4000 0000 0000 0002 will be always declined

Launch
--------------------
1. `cd stripe_test`
2. `python -m venv venv`
3. `. venv/bin/activate`
    you are free to use your favorite python enviroment utility
4. `pip install -r requiroments.txt`
5. next you need to register a test app at the stripe.com
6. add STRIPE_SECRET_KEY and STRIPE_WEBHOOK_SECRET to your local enviroment. Take the values from your stripe test app dashboard
7. `export FLASK_APP=app.py`
8. `flask run`
9. `ngrok http [port]` (optional) 
    For some time your app will be accesable from the web via public link (true magic)


based on
> https://github.com/miguelgrinberg/flask-stripe-orders
