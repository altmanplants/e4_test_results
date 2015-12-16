# Evolution 4 - Purchase Order Entry

### Items

* PV Dialog after user retrieves filtered list... and user selects a row - <kbd>ENTER</kbd> should select item  `ENTER` = `OK`
* PV Dialog - `DOUBLE CLICK` on row should select item
* TERMS dropdown is empty (assume no data in dev)
* RCPT STATUS dropdown in grid should be read only
* There are a few hidden cols in vb6 code, did we include them in E4?
* Shipper Id Validate should populate Shipper Name / shipper name is wrong
* Need some indicator that the PO has a note.  ie. when note text is not zero len then the button should highlight or something
* HG PV - when cursor is in HG Item, <kbd>ENTER</kbd> should = <kbd>Search</kbd>, when grid is focus, <kbd>Enter</kbd> should = <kbd>Ok</kbd>
* Drop-down category should dflt to user pref `Last Category`

* Vend Item is locked - should be able to enter data 
* Theme on Notes Dialog? missing
* Required by date change not staying...
* isDirty / save prompt (click new / then enter ponbr should not get save prompt)
* check if crop is on a po already if so, do not allow add to po (pv or ?)
* PV on PO Number
* 

### Discuss Copy / Paste functionality
* copy/paste existing row
* copy/paste list of crops
* copy/paste list of hg items

### Grid Control
* grid <kbd>Ctrl</kbd> + <kbd>'</kbd> = copy from cell above



### Date Control


In VB6 - the date control allows several keyboard short cuts

* <kbd>t</kbd> = today
* <kbd>+</kbd> = add one day
* <kbd>-</kbd> = subtract one day
* <kbd>CTRL</kbd> + <kbd>+</kbd> = add one week
* <kbd>CTRL</kbd> + <kbd>-</kbd> = subtract one week
* <kbd>F4</kbd> - show production week number

18423
18424
18425