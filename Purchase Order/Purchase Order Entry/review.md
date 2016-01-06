# Evolution 4 - Purchase Order Entry

### Items

	Round 1 -  
	Evolution Version: 0.0.3.0
	Branch: purchse-order
	Review Date: `12/15/2015` 

* PV Dialog after user retrieves filtered list... and user selects a row - <kbd>ENTER</kbd> should select item  `ENTER` = `OK` **DONE**
* PV Dialog - `DOUBLE CLICK` on row should select item **DONE**
* TERMS dropdown is empty (assume no data in dev) **DONE. HOW TO TEST?**
* RCPT STATUS dropdown in grid should be read only **DONE**
* There are a few hidden cols in vb6 code, did we include them in E4? **DONE**
* Shipper Id Validate should populate Shipper Name / shipper name is wrong **DONE**
* Need some indicator that the PO has a note.  ie. when note text is not zero len then the button should highlight or something **DONE**
* HG PV - when cursor is in HG Item, <kbd>ENTER</kbd> should = <kbd>Search</kbd>, when grid is focus, <kbd>Enter</kbd> should = <kbd>Ok</kbd> **DONE**
* Drop-down category should dflt to user pref `Last Category` **DONE**

* Vend Item is locked - should be able to enter data **DONE**
* Theme on Notes Dialog? missing **DONE**
* Required by date change not staying... **DONE**
* isDirty / save prompt (click new / then enter ponbr should not get save prompt) **DONE**
* check if crop is on a po already if so, do not allow add to po (pv or ?)
* PV on PO Number **DONE**
* 

### Discuss Copy / Paste functionality
* copy/paste existing row
* copy/paste list of crops
* copy/paste list of hg items

### Grid Control
* grid <kbd>Ctrl</kbd> + <kbd>'</kbd> = copy from cell above **DONE**



### Date Control


In VB6 - the date control allows several keyboard short cuts

* <kbd>t</kbd> = today **DONE**
* <kbd>+</kbd> = add one day **DONE**
* <kbd>-</kbd> = subtract one day **DONE**
* <kbd>CTRL</kbd> + <kbd>+</kbd> = add one week **DONE**
* <kbd>CTRL</kbd> + <kbd>-</kbd> = subtract one week **DONE**
* <kbd>F4</kbd> - show production week number **DONE**

18423
18424
18425


	Round 2 -  
	Evolution Version: 0.0.3.0
	Branch: purchse-order
	Review Date: `1/4/2016 10:55:03 AM `

# Evolution 4 - Purchase Order Entry

### Items

	Round 1 -  
	Evolution Version: 0.0.3.0
	Branch: purchse-order
	Review Date: `12/15/2015` 

* PV Dialog after user retrieves filtered list... and user selects a row - <kbd>ENTER</kbd> should select item  `ENTER` = `OK` **DONE**
* PV Dialog - `DOUBLE CLICK` on row should select item **DONE**
* TERMS dropdown is empty (assume no data in dev) **DONE. HOW TO TEST?**
* RCPT STATUS dropdown in grid should be read only **DONE**
* There are a few hidden cols in vb6 code, did we include them in E4? **DONE**
* Shipper Id Validate should populate Shipper Name / shipper name is wrong **DONE**
* Need some indicator that the PO has a note.  ie. when note text is not zero len then the button should highlight or something **DONE**
* HG PV - when cursor is in HG Item, <kbd>ENTER</kbd> should = <kbd>Search</kbd>, when grid is focus, <kbd>Enter</kbd> should = <kbd>Ok</kbd> **DONE**
* Drop-down category should dflt to user pref `Last Category` **DONE**

* Vend Item is locked - should be able to enter data **DONE**
* Theme on Notes Dialog? missing **DONE**
* Required by date change not staying... **DONE**
* isDirty / save prompt (click new / then enter ponbr should not get save prompt) **DONE**
* check if crop is on a po already if so, do not allow add to po (pv or ?)
* PV on PO Number **DONE**
* 

### Discuss Copy / Paste functionality
* copy/paste existing row
* copy/paste list of crops
* copy/paste list of hg items

### Grid Control
* grid <kbd>Ctrl</kbd> + <kbd>'</kbd> = copy from cell above **DONE**



### Date Control


In VB6 - the date control allows several keyboard short cuts

* <kbd>t</kbd> = today **DONE**
* <kbd>+</kbd> = add one day **DONE**
* <kbd>-</kbd> = subtract one day **DONE**
* <kbd>CTRL</kbd> + <kbd>+</kbd> = add one week **DONE**
* <kbd>CTRL</kbd> + <kbd>-</kbd> = subtract one week **DONE**
* <kbd>F4</kbd> - show production week number **DONE**

18423
18424
18425


	Round 2 -  
	Evolution Version: 0.0.3.0
	Branch: purchse-order
	Review Date: `1/4/2016 10:55:03 AM `

*	if shipper id is entered or selected from F3, screen should populate the shipper name **DONE**
*	in the date control.. .can we use the +/- key on the numeric keypad too? **DONE**
*	Ctrl - note subtracting 1 wk from date **DONE**
*	if shipper id is entered or selected from F3, screen should populate the shipper name
*	in the date control.. .can we use the +/- key on the numeric keypad too?
*	Ctrl - note subtracting 1 wk from date


	Round 3 -  
	Evolution Version: 0.0.3.0
	Branch: purchse-order
	Review Date: `1/6/2016 11:49:23 AM`

*	Need to populate Terms when vendor is selected - (test in Production)
*	Limit Entry to
	*	ShipVia = 15
	*	RefNbr = 30
	*	Buyer = 25
	*	Proj Descr = 15
	*	Shipper Id = 10
	*	Shipper Name = 30
	*	Vend Item = 30
	*	Description = 30
	*	Comment = 70
	

