### _For a discount on 2Checkout’s monthly fees, enter promo code:  GIT2CO  during signup._

Integrate PrestaShop with 2Checkout
----------------------------------------

### PrestaShop Settings:

1. Clone or download and extract git@github.com:craigchristenson/PrestaShop-2Checkout.git
2. Upload the checkout directory to the modules directory where your PrestaShop install is located on your hosting/server.
3. Go into your PrestaShop Admin Modules/Payment Gateways area, install, enable and select 2Checkout Payments.
4. Click configuration and fill out your 2Checkout account number and Secret Word.
5. Click Update Settings.

### 2Checkout Settings:

1. Sign in to your 2Checkout account.
2. Click the Account tab and Site Management subcategory.
3. Set the Approved URL to http(s)://yourcarturl.com/index.php?fc=module&module=checkout&controller=validation (Replace http://www.yourcarturl.com with the actual URL to your store.)
4. Under Direct Return select Header Redirect.
5. Enter your Secret Word.
6. Click Save Changes.

**Contact 2Checkout.com directly for integration assistance.**

Version: 1.0.0
