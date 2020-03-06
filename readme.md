# Laravel Device Seller

## Installation

1. Clone the repo and `cd` into it
1. `composer install`
1. Rename or copy `.env.example` file to `.env`
1. `php artisan key:generate`
1. Set your database credentials in your `.env` file
1. Set your Stripe credentials in your `.env` file. Specifically `STRIPE_KEY` and `STRIPE_SECRET`
1. Set your Algolia credentials in your `.env` file. Specifically `ALGOLIA_APP_ID` and `ALGOLIA_SECRET`.
1. Set your Braintree credentials in your `.env` file if you want to use PayPal. Specifically `BT_MERCHANT_ID`, `BT_PUBLIC_KEY`, `BT_PRIVATE_KEY`. If you don't, it should still work but won't show the paypal payment at checkout.
1. Set your `APP_URL` in your `.env` file. This is needed for Voyager to correctly resolve asset URLs.
1. Set `ADMIN_PASSWORD` in your `.env` file if you want to specify an admin password. If not, the default password is 'password'
1. `php artisan ecommerce:install`. This will migrate the database and run any seeders necessary.
1. `npm install`
1. `npm run dev`
1. `php artisan serve`
1. Visit `localhost:8000` in your browser
1. Visit `/admin` if you want to access the Voyager admin backend. Admin User/Password: `admin@admin.com/password`. Admin Web User/Password: `adminweb@adminweb.com/password`

## Shopping Cart Package

[hardevine/LaravelShoppingcart](https://github.com/hardevine/LaravelShoppingcart)

[url=https://ibb.co/RYYZbHc][img]https://i.ibb.co/RYYZbHc/laravel-tech-cart-1.jpg[/img][/url] [url=https://ibb.co/LP8mKDw][img]https://i.ibb.co/LP8mKDw/laravel-tech-cart-2.jpg[/img][/url] [url=https://ibb.co/9TKrJFB][img]https://i.ibb.co/9TKrJFB/laravel-tech-cart-3.jpg[/img][/url] [url=https://ibb.co/DVTpnc2][img]https://i.ibb.co/DVTpnc2/laravel-tech-cart-4.jpg[/img][/url] [url=https://ibb.co/Y0XDsnW][img]https://i.ibb.co/Y0XDsnW/laravel-tech-cart-5.jpg[/img][/url] [url=https://ibb.co/nLj5yDp][img]https://i.ibb.co/nLj5yDp/laravel-tech-cart-6.jpg[/img][/url] [url=https://ibb.co/YLVW6cP][img]https://i.ibb.co/YLVW6cP/laravel-tech-cart-7.jpg[/img][/url] [url=https://ibb.co/Qn5D4Z6][img]https://i.ibb.co/Qn5D4Z6/laravel-tech-cart-8.jpg[/img][/url] [url=https://ibb.co/r7RpcS8][img]https://i.ibb.co/r7RpcS8/laravel-tech-cart-9.jpg[/img][/url] [url=https://ibb.co/NC4911D][img]https://i.ibb.co/NC4911D/laravel-tech-cart-10.jpg[/img][/url] [url=https://ibb.co/LdNrr2x][img]https://i.ibb.co/LdNrr2x/laravel-tech-cart-11.jpg[/img][/url] [url=https://ibb.co/2y7K1Rb][img]https://i.ibb.co/2y7K1Rb/laravel-tech-cart-12.jpg[/img][/url] [url=https://ibb.co/wY7cBrb][img]https://i.ibb.co/wY7cBrb/laravel-tech-cart-13.jpg[/img][/url] [url=https://ibb.co/1TKyJFG][img]https://i.ibb.co/1TKyJFG/laravel-tech-cart-14.jpg[/img][/url] [url=https://ibb.co/7kdp9jf][img]https://i.ibb.co/7kdp9jf/laravel-tech-cart-15.jpg[/img][/url] [url=https://ibb.co/kM5zktV][img]https://i.ibb.co/kM5zktV/laravel-tech-cart-16.jpg[/img][/url] [url=https://ibb.co/MD5k3vF][img]https://i.ibb.co/MD5k3vF/laravel-tech-cart-17.jpg[/img][/url]
