# Custom offline payment methods
- Magento provides **several** out-of-the-box **offline payment methods**, such as `Banktransfer`, `Cashondelivery`, `Checkmo` and `Purchageorder`.
- When it comes to payment methods, it is **more common to use** an **online payment provider(gateway)** such as `Paypal` or `Braintree`. Sometimes, project requirements may be such that we may need a **custom coded payment method**.
- You will need to think of programmatic product import and order creation script that might specialize in some specifically labeled payment method. Thus, the payment process will be controlled by us.
- In such cases, knowing how to code our **own offline payment method** might come in handy. It is worth noting that while we can make an offline payment that will grab a user's credit card information, it is not really advisable to do so unless our infrastructure is PCI-compliant. 
