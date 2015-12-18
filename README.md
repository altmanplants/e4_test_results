# Evolution 4 Test Results

	Program review to be broken down by Module (each folder)
	Each screen being reviewed will be listed in the objects.md files and should have a folder within its' module folder
	Main review findings should be placed in a file named `review.md`
	Any features or enhancements that we feel are valid but not scheuduled for this phase of developement should go in a file name future.md
	:)


# Evolution 4 Migration Check List

## Suggested Migration Order

Risk | Module | Description | Obj Qty | Seq |
:---:|---|:---|---:|:---:|
3|CASO|Sales Order Management|20| |
1|CAAR|Accounts Receivable|1||
0|CAAP|Accounts Payable|0
1|CADI|Document Imaging|2
3|CAEC|Electronic Commerce EDI|13
1|CACM|Customer Management|13
2|CAIN|Inventory Management|32
1|CAPI|Physical Inventory|6
3|CAPP|Production Scheduling|47
0|CAPM|Price/Contract Management|0
1|CAAV|Availability Management|11
1|CAPO|Purchase Order Management|15|2
3|CARS|Routing & Scheduling|33
1|CASA|Sales Analysis|14
1|CAAC|Ad Calendar| 0
0|CATA|Time & Attendance (nothing in use)|4
1|CAIT|iTrack (all web)|15
1|CARC|RepConnect (all web)|8
1|CASS|System Admin (mostly web)|38|1


Risk - 

 * 0 - No risk
 * 1 - Very low risk, function not time critical
 * 2 - Moderate risk, fail back to E3 possible but not ideal
 * 3 - High Risk (data integrity / high usage function)

