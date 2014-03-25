ads
===

open mobfox modify version

===
System Requirements:

PHP Version 5.3 or above with MySQL support.
PHP SimpleXML Extension
PHP cURL Extension OR fsocket suppport
PHP mbstring extension

Installation Instructions:

1. Upload the contents of this directory onto a public directory on your web server.

2. Once uploaded, open the mAdserve Installation Wizard at http://www.yourserver.com/www/cp/install.php and follow the installation instructions.

Replace http://www.yourserver.com with the public address of your web server.

Implementing the mAdserve Advertising SDK:

You can find the mAdserve iOS and Android SDKs inside the /sdk directory of your mAdserve ZIP. These SDKs are required for displaying Banner and Interstitial ads inside your iOS/Android applications.

For SDK Integration instructions, please refer to the installation guides in the respective SDK folders.


More Information about mAdserve: http://www.madserve.org

If you encounter any problems or questions, please visit the mAdserve help center at http://help.madserve.org

3. execute sqls below.

INSERT INTO `md_uaccounts` VALUES ('1', 'admin@vip.com', 'e10adc3949ba59abbe56e057f20f883e', '1', '1', 'allyes', 'hao', 'qaohao', '0', '15991673551', '88888888', 'gao xin street', 'xi\'an', 'shaanxi', '710000', 'china', '086', '1', '2014-03-24');

ALTER TABLE `md_usessions` CHANGE `ip_address` `ip_adress` VARCHAR(100)DEFAULT NULL;

4. open http://www.yourserver.com/ads/www/cp/signin.php in browser, login system by administrator acount 'admin@vip.com' with password '123456'.