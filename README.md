# WooCommerce Shoppy.gg Payment Gateway (PayPal Integration)

This plugin adds full **Shoppy.gg payment support** to WooCommerce, allowing customers to pay using **PayPal via Shoppy.gg’s secure checkout system**.  
Orders are automatically confirmed through **Shoppy webhook validation**, and WooCommerce updates the status to **Processing** after successful payment.

---

## 🚀 Features

- ✔️ PayPal payments via Shoppy.gg  
- ✔️ Secure API integration  
- ✔️ Custom payment gateway added to WooCommerce  
- ✔️ Automatic order validation through Shoppy webhooks  
- ✔️ Updates WooCommerce order status to **Processing**  
- ✔️ Sends WooCommerce “Order Processing” email to customers  
- ✔️ Displays “Payment via Shoppy.gg (PayPal)” in order details  
- ✔️ Custom PayPal icon + description at checkout  
- ✔️ Compatible with the latest WordPress & WooCommerce versions  

---

## 📦 Installation

1. Download the ZIP or clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/woocommerce-shoppy-payment-gateway
2. Upload the plugin folder to: wp-content/plugins/
3. Activate the plugin from WordPress → Plugins.
4. Go to
   WooCommerce → Settings → Payments → Shoppy.gg and enter the following:
   Shoppy API Key
   Webhook Secret
   Return URL (optional)

   🔧 Configuration
Shoppy Payment API Setup

Enter your API key from:
Shoppy Dashboard → Settings → API

Webhook Setup

Add your WordPress webhook URL in Shoppy: https://yourwebsite.com/?wc-api=shoppy_webhook
Select the webhook event: order:paid
Use the same Webhook Secret that you entered in the plugin settings.

📩 Order Flow

1. Customer selects Shoppy.gg – Pay with PayPal at checkout.
2. They are redirected to Shoppy’s secure PayPal payment page.
3. After successful payment:
   Shoppy sends a webhook
   WordPress verifies the signature
   WooCommerce marks the order as Processing

4. Customer receives the Order Processing email.
5. Admin sees the note:
   “Payment received via Shoppy.gg (PayPal)”

🛠️ Requirements

WordPress 5.0+
WooCommerce 3.0+
PHP 7.2+
Shoppy.gg account

👨‍💻 Author
Vraj Patel

📜 License
GPL v2 or later.
This plugin is open-source and free to modify.
