# Production Planning Tool

<p class="lead">Production Planning Tool helps to plan production and purchase Items. A list of Items can be generated from the open Sales Orders in the system. This tool creates Production Orders and generates Material Requests.</p>

The Production Planning Tool will generate:

1. **Production Orders** for selected Items 
2. **Material Requests** for Items whose Projected Quantity is likely to fall below zero.

> Manufacturing > Production Planning Tool

The Production Planning Tool enables you to complete the production cycle in a fast and efficient manner. From procuring materials, producing goods, to updating stocks - everything is done by clicking on buttons which appear after every transaction. The tool is user friendly and does not require you to go back and forth into the system to make and log different forms. Everything is intuitive and can be performed step by step. 

You can pull Sales Orders directly by clicking on a button. Select the Sales Orders you wish to process and click on another button to get Items for that Sales Order. Mention Item details and click on the button ‘Make Production Orders’. It is that simple! After this you can click on another button and create Material Requests required to complete this Production Order. The whole process is fuss free and easy.

> Use the Production Planning Tool to make Production Order.

#### Step 1: Pull Sales Order

Sales Order is an order issued by a business to a Customer. 

__Figure 1: Sales Order__


![Get Sales Order](/assets/frappe_io/images/erpnext/e-t-o-ppt-get-so-childbed.png)


#### Step 2: Get Items from Sales Order

Select Items by clicking on the ‘Get Items from Sales Order’ button. Check the box that says ‘Use multi-level BOM’. This box is checked because you have sub-assemblies. 

__Figure 2: Pulled Items__

![Production Planning Get Items](/assets/frappe_io/images/erpnext/e-t-o-get-items-ppt-childbed.png)

#### Step 3: Create Production Order

Production Order is an order to produce a specific quantity of material within a predefined timeframe. It contains all of the relevant information required for the execution of the process, including how much should be manufactured when. 

__Figure 3: Production Order__

![Production Order](/assets/frappe_io/images/erpnext/e-t-o-ppt-create-po-childbed.png)

#### Step 4: Create Material Request

Material Request is a request to order materials for the production of your Item/product.

__Figure 4: Material Request__

![Material Request in PPT](/assets/frappe_io/images/erpnext/e-t-o-material-requests-ppt-childbed.png)

This request is created by clicking on the box ‘Create Material Request’. Click on the highlighted Material Request number. The click will open into a Material Request form. 

> Note: Remember to put your sub-assembly Items/ Item Milestones in the Bill of Material. The Material Request button will make purchase requests even for the sub-assembly raw material.

#### Quick Overview of PPT-Production Planning Tool

* Get Sales Order
* Get Items from Sales Order
* Create Production Order
* Create Material Request
* Download Materials Required


<i class="icon-lightbulb text-warning" style="font-size: 200%"></i> All the buttons on this tool work ! If you have entered the data properly, the tool will work flawlessly.

After  production planning, it is time to check the Production Order, Transfer Raw Materials and Update Finished Goods. However, before proceeding to manufacture, you are required to complete the Buying process by completing the Purchase Orders and Purchase Receipts. 



Next: [Buying](/apps/erpnext/guide-books/engineer-to-order/material-request)
