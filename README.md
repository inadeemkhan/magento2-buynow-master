# Magento 2 BuyNow 

This module add "BuyNow" button on product view page and list page to process directly checkout.

## Features:
1. Admin can manage buy now button visibility.
2. Button can be disply on the Category/Product Page.
3. Bu clicking on this button, The product will ber add into Cart directly.
4. User Friendly and Responsive.

# Installation Instruction

* Copy the content of the repo to the <b>app/code/Prince/Buynow/</b> folder
* Run command:
<b>php bin/magento setup:upgrade</b>
* Run Command:
<b>php bin/magento setup:static-content:deploy</b>
* Now Flush Cache: <b>php bin/magento cache:flush</b>

# Contribution

Want to contribute to this extension? The quickest way is to <a href="https://help.github.com/articles/about-pull-requests/">open a pull request</a> on GitHub.

# Screenshots & Support

If you encounter any problems or bugs, please <a href="https://github.com/mageprince/magento2-buynow/issues">open an issue</a> on GitHub.

<b>PRODUCT VIEW PAGE</b>

<img src="https://raw.githubusercontent.com/mageprince/all-module-screenshots/master/BuyNow/listpage.png" alt="View Page" border="0">

<b>PRODUCT LIST PAGE</b>

<img src="https://raw.githubusercontent.com/mageprince/all-module-screenshots/master/BuyNow/viewpage.png" alt="list page" border="0" />

<b>Store->Configuration->Mageprince->Buy Now->Settings</b>

<img src="https://raw.githubusercontent.com/mageprince/all-module-screenshots/master/BuyNow/admin-settings.png" alt="config settings" border="0" />

# How To Find Addtocart Form Id

Go to product view page and right click on addtocart button and click on inspect element. Then scroll up and find addtocart form id.

<img src="https://raw.githubusercontent.com/mageprince/all-module-screenshots/master/BuyNow/formid.png" alt="Form ID" border="0" />

## Prerequisites

### Use the following table to verify you have the correct prerequisites to install this Extension.
<table>
	<tbody>
		<tr>
			<th>Prerequisite</th>
			<th>How to check</th>
			<th>For more information</th>
		</tr>
	<tr>
		<td>Apache 2.2 or 2.4</td>
		<td>Ubuntu: <code>apache2 -v</code><br>
		CentOS: <code>httpd -v</code></td>
		<td><a href="https://devdocs.magento.com/guides/v2.2/install-gde/prereq/apache.html">Apache</a></td>
	</tr>
	<tr>
		<td>PHP 7.*.*</td>
		<td><code>php -v</code></td>
		<td><a href="http://devdocs.magento.com/guides/v2.2/install-gde/prereq/php-ubuntu.html">PHP Ubuntu</a><br><a href="http://devdocs.magento.com/guides/v2.2/install-gde/prereq/php-centos.html">PHP CentOS</a></td>
	</tr>
	<tr><td>MySQL 5.6.x</td>
	<td><code>mysql -u [root user name] -p</code></td>
	<td><a href="http://devdocs.magento.com/guides/v2.2/install-gde/prereq/mysql.html">MySQL</a></td>
	</tr>
</tbody>
</table>
### Feedback and Support <a href="mailto:khannadeem243@gmail.com">khannadeem243@gmail.com</a>
