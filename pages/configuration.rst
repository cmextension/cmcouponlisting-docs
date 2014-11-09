=============
Configuration
=============

After you install CM Coupon Listing, you need to configure it first. In CM Coupon Lising's Dashboard, you click Options button on the toolbar, you are taken to Config component where you can configure many options in CM Coupon Listing.

We have 9 tabs: General, Coupon types, Layout, Vote & comment, Submission page, Sharing buttons, Pagination, Access and Permissions.

General
-------

.. image:: ../images/configuration_general.jpg

* **Logo folder**: The folder where logos of merchants are stored.
* **Coupon folder**: The folder where coupons of merchants are stored.
* **Notify admin for new merchant**: Enable or disable mailing to administrators when a new merchant registers. All administrators will receive this notification mail.
* **Date format**: The date format used which is used in merchant and user's submission forms.
* **Notify admin for new coupon**: Send notification mail to administrators when there is a new coupon submitted in front-end by merchant or user.

Logo and coupon folders are inside your Joomla!'s image folder. You can configure your Joomla!'s image folder in Media Manager.

The email's templates are stored in the language file of the component, to customize the templates you can modify the language file.

Coupon types
------------

.. image:: ../images/configuration_coupon_types.jpg

* **Supported coupon types**: Coupon types that you support on your site. Only selected coupon types are displayed in front-end for users to choose.

Layout
------

.. image:: ../images/configuration_layout.jpg

* **Layout**: Use non-responsive layout or responsive layout. You can use responsive layout if you use Joomla! 3.x.x or a Joomla! template which includes Bootstrap.
* **Coupon display order**: The order of coupons in coupon list.
* **Enable coupon detail page**: Detail page shows more info about coupon. Enabling coupon detail page also gives user ability to share coupon via social networks. Coupon's detail description is disabled if coupon detail page is disabled.
* **Display get coupon button in coupon list**: If you disable coupon detail page, you should display get coupon button in coupon list so that users can get coupon. If you enable coupon detail page, you can hide the button in coupon list, users need to view detail page to get coupon.
* **jQuery**: Load an internal jQuery file inside your Joomla! installation or an external jQuery file. For example, if your jquery.js is placed in media/js/ folder, you could enter "media/js/jquery.js", or if you could use Google's jQuery "//ajax.googleapis.com/ajax/libs/jquery/1.10.2/jquery.min.js".
* **Category list's column quanity**: Category list page displays categories and merchants in those categories, the list is displayed as columns.
* **Sub-category's left indent**: Children categories are displayed right below their parent category, you can use spaces or symbols to separate these categories from the left margins, let's us easily recognize that they are children category. This setting is used in both back-end and front-end. You can use HTML entity name, eg &nbsp; for a space or &#8594; for a right arrow.

.. _ref-configuration-vote-comment:

Vote & comment
----------------

.. image:: ../images/configuration_vote_comment.jpg

* **Vote**: Enable or disable vote.
* **Who can vote**: Only users in selected access level can vote.
* **Ask questions**: When voting, ask user what he/she bought and how much he/she saved (good coupon), or the reason why coupon didn't work (bad coupon).
* **Comment**: Enable or disable comment.
* **Who can comment**: Only users in selected access level can comment.
* **Captcha**: Use the captcha plugin in comment form. You may need to enter required information for your captcha plugin in the Plugin Manager.
* **Comment's pagination**: The number of comments which are displayed below coupon, this is also the number of comments which are loaded next when user want to view more comments.

.. _ref-configuration-submission-page:

Submission page
---------------

.. image:: ../images/configuration_submission_page.jpg

* **Access submission page**: Only users who are in the selected access level can access submission page to submit new coupon.
* **Return page**: The page where user is taken to after a successful submission.
* **Captcha**: Use the captcha plugin in submission form. You may need to enter required information for your captcha plugin in the Plugin Manager.

Printable coupon
----------------

.. image:: ../images/configuration_printable_coupon.jpg

These options are only used for non-repsonsive layout.

* **Coupon image's max width in download modal**: Allowed maximum width in pixel of coupon image which is displayed in download modal. If coupon image's width is greater than this value, coupon image's width is forced to display in this value. This value should be smaller than modal's width.
* **Coupon image's max height in download modall**: Allowed maximum height in pixel of coupon image which is displayed in download modal. If coupon image's height is greater than this value, coupon image's height is forced to display in this value. This value should be smaller than modal's height.
* **Download modal's widthl**: Width of coupon download modal in pixel.
* **Download modal's heightl**: Height of coupon download modal in pixel.

Sharing buttons
---------------

.. image:: ../images/configuration_sharing_buttons.jpg

* **Share coupon buttons on coupon list**: Display sharing buttons for coupon on coupon list page.
* **Share coupon buttons on coupon detail**: Display sharing buttons for coupon on coupon detail page.
* **Share merchant buttons on merchant list**: Display sharing buttons for merchant on merchant list page.
* **Share merchant buttons on merchant detail**: Display sharing buttons for merchant on merchant detail page.

Pagination
----------

.. image:: ../images/configuration_pagination.jpg

* **Limit**: Number of items displayed per page. Only applied for coupon list in categories, merchant list. Not applied for coupon list in merchant detail page.
* **Display Select**: Whether to show or hide the Display Select dropdown listbox.
* **Table Headings**: Show or Hide the headings in list layouts.
* **Pagination**: Show or hide Pagination support. Pagination provides page links at the bottom of the page that allow user to navigate to additional pages. These are needed if the information will not fit on one page.
* **Pagination Results**: Show or hide pagination results information, for example, "Page 1 of 4".

Access
------

.. image:: ../images/configuration_access.jpg

* **Coupon's default access level**: The access level group that is allowed to view coupons. This setting is applied for new coupons submitted by merchants and users in front-end.

Permissions
-----------

.. image:: ../images/configuration_permission.jpg

Default permissions used in CM Coupon Listing. The component doesn't support access level group in back-end so actions Create, Delete, Edit, Edit State and Edit Own are not supported.