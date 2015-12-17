# Evolution 4 - Purchase Order Entry

### Items

	Round 1 -  
	Evolution Version: 0.0.3.0
	Branch: purchse-order
	Review Date: `12/15/2015` 

* PV Dialog after user retrieves filtered list... and user selects a row - <kbd>ENTER</kbd> should select item  `ENTER` = `OK` **DONE**
* PV Dialog - `DOUBLE CLICK` on row should select item **DONE**
* TERMS dropdown is empty (assume no data in dev) **HOW TO TEST?**
* RCPT STATUS dropdown in grid should be read only **DONE**
* There are a few hidden cols in vb6 code, did we include them in E4? **DONE**
* Shipper Id Validate should populate Shipper Name / shipper name is wrong
* Need some indicator that the PO has a note.  ie. when note text is not zero len then the button should highlight or something **DONE**
* HG PV - when cursor is in HG Item, <kbd>ENTER</kbd> should = <kbd>Search</kbd>, when grid is focus, <kbd>Enter</kbd> should = <kbd>Ok</kbd> **DONE**
* Drop-down category should dflt to user pref `Last Category`

* Vend Item is locked - should be able to enter data 
* Theme on Notes Dialog? missing **DONE**
* Required by date change not staying... **DONE**
* isDirty / save prompt (click new / then enter ponbr should not get save prompt)
* check if crop is on a po already if so, do not allow add to po (pv or ?)
* PV on PO Number **DONE**
* 

### Discuss Copy / Paste functionality
* copy/paste existing row
* copy/paste list of crops
* copy/paste list of hg items

### Grid Control
* grid <kbd>Ctrl</kbd> + <kbd>'</kbd> = copy from cell above **DONE NEEDS TO BE TESTED**



### Date Control


In VB6 - the date control allows several keyboard short cuts

* <kbd>t</kbd> = today
* <kbd>+</kbd> = add one day
* <kbd>-</kbd> = subtract one day
* <kbd>CTRL</kbd> + <kbd>+</kbd> = add one week
* <kbd>CTRL</kbd> + <kbd>-</kbd> = subtract one week
* <kbd>F4</kbd> - show production week number **WHAT IS THIS?**

18423
18424
18425