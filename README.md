# IRR_Calculator_Tool
This tool reads data pulled from a ClearStructure database and constructs an inception to data close out report. Close out means all completely sold positions/paid off securities.
This is not at the trade lot level, but rather at the position level. The constructed database is then analyzed by the XIRR tool and a number of calculated columns.
A summary table is constructed and appened to excelwriter. All cashflow tables are then appended to a second tab with appropriate formatting. The output is then exported to excel.
