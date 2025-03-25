# Magento 2 Return Request (RMA) Extension

## Introduction
The **Magento 2 Return Request (RMA) Extension** by CodeDecorator enhances the return process for eCommerce stores. This extension allows customers to initiate and manage return requests smoothly, improving customer satisfaction and trust. With an intuitive interface and advanced features, it simplifies refunds, exchanges, and store credit management while streamlining the admin workflow.

## How It Works - Magento 2 Return Request (RMA) Extension
Magento 2 RMA Extension enables customers to request product returns easily. Customers can choose return reasons, upload images, and track return statuses from their accounts. The admin can approve, reject, or modify requests and notify customers automatically. 

This extension integrates seamlessly with Magento’s order management system, ensuring a hassle-free return process for both customers and store owners.

## Key Features
- **Seamless Return Management** – Customers can initiate return requests effortlessly.
- **Customizable Return Reasons** – Store owners can set predefined return reasons.
- **Guest User Support** – Non-registered users can also request returns.
- **Automated Notifications** – Email alerts for every return status update.

## Flexible Return Request System
Customers can submit return requests directly from their account dashboard, selecting reasons and uploading images for verification. Admins can review and process requests with ease.

## Custom Return Reasons
Store owners can define custom return reasons and policies, ensuring better return handling and transparency.

## Guest RMA Requests
Even non-registered users can request returns, improving the user experience and conversion rates.

## Email Notifications
Automated email notifications keep customers informed about their return status, reducing manual follow-ups.

## Extension Installation
To install the **Magento 2 Return Request (RMA) Extension**, follow these steps:

### Step 1: Install the extension using Composer
```sh
composer require codedecorator/magento2-rma
```
For a specific version:
```sh
composer require codedecorator/magento2-rma:1.0.0
```
*Note: You may need authentication keys from the vendor or Magento Marketplace.*

### Step 2: Run the following Magento commands
```sh
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy -f
php bin/magento cache:flush
```

## How To Configure Magento 2 Return Request (RMA) Extension

### Step 1 - Enable the Extension
Navigate to **Stores > Configuration > CodeDecorator > RMA Settings** and enable the extension.

### Step 2 - Set Return Reasons
Go to **Sales > Returns > Manage Return Reasons** to customize available return reasons.

### Step 3 - Configure Email Notifications
Under **Stores > Configuration > RMA Email Settings**, set up email templates for return requests and status updates.

### Step 4 - Manage Requests
View and manage all return requests under **Sales > Returns** in the Magento admin panel.

## Download Our [Magento 2 Return Request (RMA)](https://codedecorator.com/magento-2-return-request-rma.html) Extension
