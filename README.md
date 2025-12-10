# WooCommerce-Shoppy.gg-Payment-Gateway-PayPal-Integration

This plugin adds full Shoppy.gg payment support to WooCommerce, allowing customers to pay using **PayPal via Shoppy.gg’s secure checkout system**.  
Orders are automatically confirmed through **Shoppy webhook validation**, and WooCommerce status updates correctly to *Processing* after successful payment.

---

## 🚀 Features

- ✔️ PayPal payments via Shoppy.gg  
- ✔️ Secure API integration  
- ✔️ Custom payment gateway added to WooCommerce  
- ✔️ Automatic order validation through Shoppy webhooks  
- ✔️ Order status updates to **Processing** after payment  
- ✔️ Sends WooCommerce "Order Processing" email to customer  
- ✔️ Shows "Payment via Shoppy.gg (PayPal)" in admin order details  
- ✔️ Includes custom PayPal icon + description on checkout  
- ✔️ Works with latest WooCommerce & WordPress versions  

---

## 📦 Installation

1. Download the ZIP or clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/woocommerce-shoppy-payment-gateway

2. Upload the plugin to:
wp-content/plugins/

3. Activate it from WordPress → Plugins.

4. Go to
WooCommerce → Settings → Payments → Shoppy.gg
and enter:

Your Shoppy API Key

Your Webhook Secret

Your Return URL (optional)

🔧 Configuration
Shoppy Payment API Setup

Enter your API key from:
Shoppy Dashboard → Settings → API

Webhook Setup

Add your WordPress webhook URL in Shoppy:
https://yourwebsite.com/?wc-api=shoppy_webhook

Set the webhook event:

order:paid

And use the same Webhook Secret you entered in the plugin settings.

📩 Order Flow

Customer chooses Shoppy.gg – Pay with PayPal at checkout.

They are redirected to Shoppy’s secure PayPal payment page.

After payment:

Shoppy sends webhook → WordPress verifies signature.

WooCommerce marks order as Processing.

Customer receives confirmation email.

Admin sees:
Payment received via Shoppy.gg (PayPal)

🛠️ Requirements

WordPress 5.0+

WooCommerce 3.0+

PHP 7.2+

Shoppy.gg account

👨‍💻 Author
Vraj Patel

📜 License

GPL v2 or later.


