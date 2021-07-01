# EmailHelper

This module is simply allows you to send email. You don't need to write code in order to send Email from your custom module. Just install EmallHelper Module and inject MagentoKid\EmailHelper\Helper\Email inside your class and call sendEmail() function with appropriate paramters

**$templateID** - Identifier of your email template
**$sendtoName** - Name of Recipient
**sendtoName** -  Email of Recipient
**$senderFrom** - Sender From Identifier. By default contact, (Available identifier: general, sales, sales, contact, contact, custom2)
**variables** - Variables which are used in email template
**senderCC** - CC Recipient list in form of array
**attchmentFile** - Pass Attachement link with full path if any, default null
**bccArray** -  BCC Recipient list in form of array

**Installation Steps:**

git clone https://github.com/magentokid/EmailHelper.git
put inside app/code/MagentoKid/EmailHelper

php bin/magento setup:upgrade --keep-generated
php bin/magento setup:di:compile


