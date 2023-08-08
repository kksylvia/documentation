===================
Quotation templates
===================

Creating custom quotation templates saves a lot of time. By using pre-configured quotation
templates, completed quotations are able to be sent at a much faster pace.

Configuration
=============

In order to create custom quotation templates, the *quotation template* feature must be enabled. To
do that, navigate to :menuselection:`Sales app --> Configuration --> Settings`, and scroll to the
:guilabel:`Quotations & Orders` heading.

In that section, check the box beside the :guilabel:`Quotation Templates` feature. Doing so reveals
a new :guilabel:`Default Template` field, in which a default quotation template can be chosen from a
drop-down menu.

.. image:: quote_template/quotations-templates-setting.png
   :align: center
   :alt: How to enable quotation templates on Odoo Sales.

Also, upon activating the :guilabel:`Quotation Template` feature, a direct link to the
:guilabel:`Quotation Templates` page appears beneath the :guilabel:`Default Template` field on the
:guilabel:`Settings` page. Clicking that link reveals the :guilabel:`Quotation Templates` page, from
which templates can be created, viewed, and edited.

Before leaving the :guilabel:`Settings` page, don't forget to click the :guilabel:`Save` button to
activate the feature(s), and save all changes.

Create quotation templates
==========================

To view all quotation templates, click the :guilabel:`Quotation Templates` link on the
:guilabel:`Settings` page, or navigate to :menuselection:`Sales app --> Configuration --> Quotation
Templates`. Both options reveal the :guilabel:`Quotation Templates` page, where quotation templates
can be created, viewed, and edited.

To create a new quotation template, click the :guilabel:`New` button, located in the upper-left
corner.

.. image:: quote_template/quotation-templates-page.png
   :align: center
   :alt: Quotation templates page in the Odoo Sales application.

Doing so reveals a blank quotation template form that can be customized in a number of ways.

.. image:: quote_template/blank-quotation-form.png
   :align: center
   :alt: Create a new quotation on a blank quotation form on Odoo Sales.

Start by entering a name for the template in the :guilabel:`Quotation Template` field. Then, in the
:guilabel:`Quotation expires after` field, designate how many days the quotation template will
remain valid for, or leave the field on the default `0` to keep the template valid indefinitely.

If the :guilabel:`Online Signature` and/or :guilabel:`Online Payment` feature is activated in the
:guilabel:`Settings` page (:menuselection:`Sales app --> Configuration --> Settings`), there is an
:guilabel:`Online confirmation` field.

In this field, check the box beside :guilabel:`Signature` to request an online signature from the
customer to confirm an order. Check the box beside :guilabel:`Payment` in the :guilabel:`Online
confirmation` field to request an online payment from the customer to confirm an order. Both options
can be enabled simultaneously, if desired.

Next, in the :guilabel:`Confirmation Mail` field, click the blank field to reveal a drop-down menu.
From the drop-down menu, select a pre-configured email template to be sent upon confirmation of an
order.

.. tip::
   To create a new email template directly from the :guilabel:`Confirmation Mail` field, start
   typing the name of the new email template, and select either: :guilabel:`Create` or
   :guilabel:`Create and edit...` from the drop-down menu that appears.

   Selecting :guilabel:`New` creates the email template, which can be edited later. Selecting
   :guilabel:`Create and edit...` creates the email template, and a :guilabel:`Create Confirmation
   Mail` pop-up window appears, in which the email template can be customized and configured right
   away.

   .. image:: quote_template/create-confirmation-mail-popup.png
      :align: center
      :alt: Create confirmation mail pop-up window from the quotation template form in Odoo Sales.

   When all modifications are complete, click :guilabel:`Save & Close` to save the email template,
   and return to the quotation form.

In the :guilabel:`Company` field, if working in a multi-company environment, designate to which
company this quotation template applies.

And, in the :guilabel:`Recurrence` field, click the blank field to reveal a drop-down menu, and
choose from a variety of pre-configured amounts of time (e.g. :guilabel:`Monthly`,
:guilabel:`Quarterly`, etc.) to designate how often this quotation template should occur.

Beneath those fields are three tabs: :guilabel:`Lines`, :guilabel:`Optional Products`,
:guilabel:`Confirmation`.

Lines tab
---------

In the :guilabel:`Lines` tab, products can be added and organized to the quotation template.

.. image:: quote_template/lines-tab-quotation-template.png
   :align: center
   :alt: Populated lines tab on a quotation template form in Odoo Sales.

To add a product to a quotation template, click :guilabel:`Add a product` in the :guilabel:`Lines`
tab of a quotation template form. Doing so reveals a blank field in the :guilabel:`Product` column.

When clicked, a drop-down menu with products from the database appear. Select the desired product
from the drop-down menu to add it to the quotation template.

.. tip::
   If the desired product isn't readily visible, type the name of the desired product in the field,
   and the option appears in the drop-down menu. Then, select that desired product to add it to the
   quotation template.

.. note::
   When a product is added, the default :guilabel:`Quantity` is `1`, but that can be edited at any
   time.

Then, drag-and-drop the product to the desired position, via the :guilabel:`six squares` icon,
located to the left of each line item.

To add a section, click :guilabel:`Add a section` in the :guilabel:`Lines` tab. When clicked, a
blank field appears, in which the desired name of the section can be typed. When the name has been
entered, click away to secure the section name.

Then, drag-and-drop the section name to the desired position, via the :guilabel:`six squares` icon,
located to the left of each line item.

To add a note, which would appear as a piece of helpful (or informative) text for the customer on
the quotation, click :guilabel:`Add a note` in the :guilabel:`Lines` tab. When clicked, a blank
field appears, in which the desired note can be typed. When the note has been entered, click away to
secure the note.

Then, drag-and-drop the note to the desired position, via the :guilabel:`six squares` icon, located
to the left of each line item.

To delete any line item from the :guilabel:`Lines` tab (product, section, and/or note), click the
:guilabel:`trash can 🗑️` icon.

Optional products tab
---------------------

In the :guilabel:`Optional Products` tab, optional products can be added to the quotation template.
Optional products can be strategically added to a quotation to entice the customer to buy additional
items to complement their original purchase, or a more expensive version of their initial item.

.. image:: quote_template/optional-products-tab-quotation-template.png
   :align: center
   :alt: Populated optional products tab on a quotation template in Odoo Sales.

To add an optional product to a quotation template, click :guilabel:`Add a line` in the
:guilabel:`Optional Products` tab. Doing so reveals a blank field in the :guilabel:`Product` column.

When clicked, a drop-down menu with products from the database appear. Select the desired product
from the drop-down menu to add it as an optional product to the quotation template.

To delete any line item from the :guilabel:`Optional Products` tab, click the :guilabel:`trash can
🗑️` icon.

.. note::
   Optional products are **not** required.

Terms & conditions tab
----------------------

The :guilabel:`Terms & Conditions` tab provides the opportunity to add terms and conditions to the
quotation template. To add terms and conditions to the quotation template, simply type (or
copy/paste) the desired terms and conditions in this tab.

.. image:: quote_template/terms-and-conditions-tab.png
   :align: center
   :alt: Terms and conditions tab in a quotation template form in Odoo Sales.

.. note::
   Terms and conditions are **not** required.

Design quotation templates
==========================

In the upper-left corner of the quotation template form, there's a :guilabel:`Design Template`
button.

.. image:: quote_template/design-template-button.png
   :align: center
   :alt: Design template button in the upper-left corner of quotation template form.

When clicked, Odoo reveals a preview of the quotation template, through the Odoo *Website*
application, as it will appear on the front-end of the website to the customer.

Odoo uses numerous blue placeholder blocks to signify where certain elements will be, and what they
will contain (e.g. :guilabel:`Template Header`, :guilabel:`Product`, etc.).

There is also a blue banner at the top of the quotation template design with a link to quickly
return :guilabel:`Back to edit mode`. When clicked, Odoo returns to the quotation template form in
the back-end of the *Sales* application.

To edit the content, look, and overall design of the quotation template, via the *Website*
application, click the :guilabel:`Edit` button in the upper-right corner.

.. image:: quote_template/design-template-edit-button.png
   :align: center
   :alt: Design template edit button in the upper-right corner of quotation template design.

When :guilabel:`Edit` is clicked, Odoo reveals a sidebar filled with a variety of design elements
and feature-rich building blocks. These building blocks can be dragged-and-dropped anywhere on the
quotation template design.

.. image:: quote_template/design-quotation-building-blocks.png
   :align: center
   :alt: Design quotation template building blocks sidebar in Odoo Website.

After it's been dropped in the desired position, it can be customized and configured to fit any
unique need, look, or style.

.. tip::
   Quotation template design uses the same methodology and functionality with design building blocks
   as a typical web page design with Odoo *Website*. Be sure to check out the
   :doc:`/applications/websites/website` documentation to learn more.

When all blocks and customizations are complete, click the :guilabel:`Save` button to put those
configurations into place.

Use quotation templates
=======================

When creating a quotation (:menuselection:`Sales app --> New`), choose a pre-configured template in
the :guilabel:`Quotation Template` field drop-down menu.

.. image:: quote_template/quotations-templates-field.png
   :align: center
   :alt: Quotation templates field on a standard quotation form in Odoo Sales.

To view what the customer will see, click the :guilabel:`Preview` button on the quotation form to
see how the quotation template appears on the front-end of the website.

.. image:: quote_template/quotations-templates-preview.png
   :align: center
   :alt: Customer preview of a quotation template in Odoo Sales.

.. seealso::
   - :doc:`/applications/sales/sales/send_quotations/get_signature_to_validate`
   - :doc:`/applications/sales/sales/send_quotations/get_paid_to_validate`
