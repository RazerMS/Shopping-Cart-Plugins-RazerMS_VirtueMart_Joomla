MOLPay Joomla VirtueMart Plugin
=====================

MOLPay Plugin for Joomla VirtueMart Shopping Cart developed by MOLPay R&D team.


Supported version
-----------------
[Joomla 2.5.x and VirtueMart 2.6.x above](https://github.com/MOLPay/VirtueMart_Plugin/blob/master/distribution/molpay_joomla2.5_vm2.zip?raw=true)

[Joomla 3.3.x and VirtueMart 3.x.x below](https://github.com/MOLPay/VirtueMart_Plugin/blob/master/distribution/molpay_joomla3.3_vm3.zip?raw=true)

Notes
-----

MOLPay Sdn. Bhd. is not responsible for any problems that might arise from the use of this module. 
Use at your own risk. Please backup any critical data before proceeding. For any query or 
assistance, please email support@molpay.com 


Installations
-------------

1. Download or clone this repository.

2. Copy [molpay_joomla2.5_vm.zip](https://github.com/MOLPay/VirtueMart_Plugin/blob/master/distribution/molpay_joomla2.5_vm2.zip?raw=true) or [molpay_joomla3.3_vm3.zip](https://github.com/MOLPay/VirtueMart_Plugin/blob/master/distribution/molpay_joomla3.3_vm3.zip?raw=true) from distribution folder.

3. Login into joomla administration panel and navigate to Extension -> Extension Manager.

4. At field Upload Package File, Upload and Install the [molpay_joomla2.5_vm.zip](https://github.com/MOLPay/VirtueMart_Plugin/blob/master/distribution/molpay_joomla2.5_vm2.zip?raw=true) or [molpay_joomla3.3_vm3.zip](https://github.com/MOLPay/VirtueMart_Plugin/blob/master/distribution/molpay_joomla3.3_vm3.zip?raw=true).

5. At the same page, click manage and find VMPAYMENT_MOLPAY from the list and ensure the status is enable (color green).

6. Next, navigate to Components -> VirtueMart. Under shop sidebar menu, Click on the Payment Methods link.

7. Click "New" button at the configuration menu (beside "EDIT").

8. Please fill the required fields.  
  - Payment Name : MOLPay
  - Self alias : -empty-
  - Publish : Yes
  - Payment Description : Malaysia Online Payment Gateway
  - Payment Method : VM Payment plugin MOLPay
  - Shopper Group : -ignore-
  - List Order : -ignore-  
  
9. On the configuration tab, fill the required fields.
  - MOLPay Merchant ID
  - MOLPay Verify Key

10. Save the configuration and test with our sandbox account.

11. Login into MOLPay Merchant Admin and set Callback URL

  ``CallbackURL: http://shoppingcarturl/index.php?option=com_virtuemart&view=pluginresponse&task=pluginresponsereceived`` 
  
*Replace `shoppingcarturl` with your shoppingcart domain 

Contribution
------------

You can contribute to this plugin by sending the pull request to this repository.


Issues
------------

Submit issue to this repository or email to our support@molpay.com


Support
-------

Merchant Technical Support / Customer Care : support@molpay.com <br>
Sales/Reseller Enquiry : sales@molpay.com <br>
Marketing Campaign : marketing@molpay.com <br>
Channel/Partner Enquiry : channel@molpay.com <br>
Media Contact : media@molpay.com <br>
R&D and Tech-related Suggestion : technical@molpay.com <br>
Abuse Reporting : abuse@molpay.com
