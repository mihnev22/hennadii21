# Accept a Payment with Elements and the Checkout Sessions API

## Set Price ID

In the back end code, replace `{{PRICE_ID}}` with a Price ID (`price_xxx`) that you created.

## Running the sample

1. Build the server

~~~
composer install
~~~

2. Run the server

~~~
php -S 127.0.0.1:4242 --docroot=public
~~~

3. Go to [http://localhost:4242/checkout.html](http://localhost:4242/checkout.html)