========
Overview
========

CM Coupon Listing is a Joomla! component which gives you ability to setup a coupon listing website, where merchants or customers can register and submit discount offers like coupon code, coupon image, discount activation link, affiliate link; this helps the merchants promote their trademarks, promote their services and earn more sales, this also helps customers purchase for their favorite products and services with discount prices.

License
-------

CM Coupon Listing is released under `GNU Public License version 2 or later <http://www.gnu.org/licenses/gpl-2.0.html>`_.

Technical Requirements
----------------------

* Joomla! 3.x.x: The latest stable release of Joomla! is always recommended for stability and security. Please check `Joomla!'s Technical Requirements <http://www.joomla.org/technical-requirements.html>`_ for more information.
* Joomla! 2.5.x: CM Coupon Listing could run on Joomla! 2.5.x. However we don't test all of CM Coupon Listing features on Joomla! 2.5.x because Joomla! 2.5 is not supported by Joomla! any more. Please update to Joomla! 3 if possible.
* Bootstrap 2 or Bootstrap 3: Your site needs to have Bootstrap 2 or 3. If you don't use Bootstrap, you may need to override the output of CM Coupon Listing to add your own CSS classes.

Additional extensions
---------------------

* CMCouponListing Category List module: a module listing all categories.
* CMCouponListing Featured Merchants module: a module showing random featured merchants.
* CMCouponListing Search module: a module showing a search form.
* cmcouponlistingmerchant plug-in: a plug-in for integration with `Akeeba Subscription <https://www.akeebabackup.com/products/akeeba-subscriptions.html>`_ component, a merchant is automatically created in CMCouponListing when he/she subscribes a subscription in Akeeba Subscription component. Merchant is inactive when subscription expires.
* tagcmcouponlising plug-in: a tag plug-in for `ACYMailling <https://www.acyba.com>`_, this helps you insert many coupons from a specific category into ACYMailing's newsletter automatically.
* CMCouponListing Merchant's Coupons: a plug-in to insert list of coupons from a specific merchant into Joomla! article, Custome HTML module or any extension which supports onContentPrepare event.

Main features
-------------

**Front-end**:

* Support Bootstrap 2 and Bootstrap 3.
* Menu item for listing all coupons, coupons in specific categories.
* Menu item for listing all categories and merchants in them.
* Menu item for listing all merchants.
* Menu item for search page.
* Coupons from featured merchants or featured coupons can be displayed on the top of coupon list.
* Merchant's management area, where merchant edits profile and manages coupons.
* Integrate with Akeeba Subscription, only active merchant can access management area, when merchant's subscription expires his/her account is deactivated so he/she can't access this area any more, unless he/she extends the subscription in Akeeba Subscription.
* Merchant can upload his/her own logo image.
* Merchant can create, edit and delete his/her own coupons.
* Registration form for user to sign up as a merchant.
* Facebook, Twitter and Google+ sharing for coupon and merchant.
* Coupon detail page.
* Support Joomla!'s access control. Coupon can be configured to available to a specific user group, this give you ability to deliver special coupons to special users, for example, users who pay for monthly fee to have access to special offers.
* Merchant registration settings inherit from Users component's settings.
* Merchant logo upload settings inherit from Media component's settings.
* User feedback for working coupon and not working coupon.
* Ask user for how much user saves (for example $50, 10€) and what user purchases if coupon works.
* Ask user for the reason why coupon doesn't work.
* User can post comment for coupon.
* Print coupon or download coupon image (for printable coupon only).

**Back-end**:

* Manage category, merchant, coupon.
* Manage where coupon images and logo images are stored.
* Enable or disable Facebook, Twitter and Google+ buttons.
* Enable or disable coupon detail page.
* Control where users can get offers, in coupon listing page or in coupon detail page.
* Manage users's votes.
* Manage users's comments.
* Ability to setup custom reasons for not working coupons.
* Ability to setup currencies for asking how much user saves.
