# Purchase Order Review

## PO Approval

	Round 1 -  
	Evolution Version: 0.0.3.0
	Branch: purchse-order
	Review Date: `12/16/2015 2:49:08 PM` 


* Spacebar should select/un-select check box **DONE**
* make right col auto fill width **DONE**
* Evo 3 allows user to select Rows and/or Row ranges and check groups (see image below) **DONE**
* Approve should prompt user for yes/no confirmation **DONE**
* my test returned `Error: The remote server returned an error: (500) Internal Server Error.` **UNABLE TO REPRODUCE**
* Thinking `ROW` select method would be better than cell select on grid **DONE**
* would be nice to enable col header filters (nice to have / enhancement) **DONE**
* `Select All` and `Clear All` are really Select & Clear selected grid rows **DONE**


![](http://i.imgur.com/YDLMK2H.png)


<hr>

	
	Round 2 -  
	Evolution Version: 0.0.3.0
	Branch: purchse-order
	Review Date: `1/4/2016 10:46:55 AM ` 

*	if user click on 'x' link to close the HTML page in the preview pane... the user is unable to view another po, exception occurs on line: 202 of UserControlPurchaseOrderApproval.cs.  Can we either prevent the webBrowswerPO control from being set to NULL or test/catch null exception just in case user clicks the 'x' **DONE - removed javascript close from xslt RB**


	Round 3 -  
	Evolution Version: 0.0.3.0
	Branch: purchse-order
	Review Date: `1/5/2016 8:02:35 AM `

Ready for user testing. RB 