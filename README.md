Housekeeping

Hardcoded Values = Blue
Calculated Values = Black
Referenced Values = Green

Hours:Minutes:Seconds

--------------------------------------------------------------------------

(GitHub Published) Multifamily Model_Pierre Elie Mattijs_Sep-22-26.xlsx

Step 1 00:15:06

Sheet Summary:
- Property Details Box
- Acquisition Assumptions Box
- Rent Roll Summary Box

Step 2 00:21:01

Sheet Summary:
- Market Assumptions Box

Step 3 00:29:38

Sheet Monthly Cash Flow:
- Rows 4-17: Projecting Summary Sheet Assumptions

Step 4 00:39:14

Sheet Summary:
- Rows 24-36: Income and Expense Summary Box 

Step 5 00:51:12 

Sheet Summary:
- Rows 38-61: Income and Expense Summary Box

Step 6 01:03:07

Sheet Monthly Cash Flow:
- Rows 19-30: Projecting Rows 24-36 from the Income and Expense Summary Box on a Monthly Basis 

Step 7 01:17:10

Sheet Monthly Cash Flow:
- Rows 32-55: Projecting Rows 38-61 from the Income and Expense Summary Box on a Monthly Basis 

Step 8 01:32:03

Sheet Summary:
- Financing Box
- Finance Sizing Box

Step 9 01:50:12

Sheet Debt:
- Assumptions Box
- Amortization Schedule Box

Step 10 02:03:15

Sheet Summary:
- Disposition Analysis Box

Step 11 02:39:37

Sheet Monthly Cash Flow:
- Unlevered Cash Flows Box
- Unlevered Metrics Box 
- Levered Cash Flows Box
- Unlevered Metrics Box

Sheet Summary:
- Returns Summary Box

--------------------------------------------------------------------------

(GitHub Published) Multifamily Value Add Model_Pierre Elie Mattijs_Sep-23-26.xlsx

In this second model, I build on the first model by implementing a value-add strategy. The objective is to calculate the costs associated with the building renovations and the resulting additional revenue. But before going further, I noticed a formatting mistake in the first model in the Monthly Cash Flow tab. I corrected it and then proceeded with the steps below.

Step 1 00:08:21

Sheet Rehab: 
- Interior Improvements Box
- Exterior Improvements Box

Step 2 00:19:31

Sheet Summary:
- Rehab Summary Box

Step 3 00:45:14

Sheet Rehab:
- Rehab Schedule Box 

Step 4 00:57:46

Sheet Monthly Cash Flow:
- Added Row 21 Renovation Premium 
- Added Row 22 GPR Post Renovation 
- Modified Row 23 Loss to Lease
- Modified Row 24 GSR 
- Added Row 15 Rehab Vacancy 
- Added Row 26 Rehab Vacancy 

Sheet Summary:
- Added Row 18 Renovation Costs, in the Acquisition Assumptions Box

Sheet Monthly Cash Flow:
- Added Row 67 Rehab Costs
- Added Row 83 Rehab Costs

Step 5 01:02:02

Sheet Summary:
- Modified Row 34 from Net Operating Income to NOI Post Renovations
- Modified Row 35 from Purchase price to Total Capitalization

--------------------------------------------------------------------------

(GitHub Published) Multifamily Development Model_Pierre Elie Mattijs_Sep-24-26

In this third model, I start from the first model and reuse some of the original data. I modify to cater it to a development project.

On the Summary sheet, the boxes I keep are:

Property Details
Rent Roll Summary
Market Assumptions
Income and Expense Summary

For the Income and Expense Summary, I rename the figures from Model 1 as Untrended and add a separate column for the Trended figures.

I also:

Delete the Closing Date row 11 and make some design changes compared with Model 1. Indeed, the acquisition box, exit logic and financing are reworked for development.
The Monthly Cash Flow sheet is kept largely similar. However, A whole income statement section is added, but this one will be used to account for the lease up timing (See step 4).
Debt sheet is also kept similar but us linked to the new Permanent Financing Box in the Summary tab.


Step 1

Sheet Summary:
- I add a Timing box in rows 5–8.

Step 2

Sheet Summary:
- I add row 24: Absorption (Units/Mo)

Sheet Lease Up:
- Complete the full sheet.

Sheet Summary:
- Added rows 8–10 in the Timing box, starting from Q8.

Step 3

Sheet Monthly Cash Flow:
- Completed rows 57-72.

Step 4

Sheet Monthly Cash Flow:
- Completed rows 54-97.

Step 5

Sheet Budget:
- Worked on the overall design of the sheet, then completed rows 11–45.

Step 6

Sheet Budget:
- Completed rows 4-7.
- Completed rows 10-38, starting from column F.

Step 7

Sheet Summary:
- Completed rows 13-17 of the Sources Box
- Referenced the origination costs on the budget sheet D43
- Completed the Construction Financing Box

Sheet Construction Debt:
- Completed rows 4-16

Step 8

Sheet Construction Debt:
- Completed rows 20-25
- Referenced Net Interest on the budget sheet D44

Sheet Summary:
- Completed Sources in the Uses and Sources Box

Step 9

Sheet Summary:
- Completed Trended Columns in the Income and Expense Summary Box

Step 10

Sheet Summary:
- Completed the Permanent Financing Box

Sheet Debt: 
- Put new inputs in the Assumptions Box  

Step 11

Sheet Summary:
- Completed the Finance Sizing Box

Step 12 

Sheet Monthly Cash Flows:
- Completed the Unlevered Cash Flows and Unlevered Returns Metrics Boxes 

Sheet Summary:
- Completed the Unlevered Column in the Returns Summary Box 

Step 13

Sheet Monthly Cash Flows:
- Completed the Levered Cash Flows and Levered Returns Metrics Boxes

Sheet Summary:
- Completed the Levered Column in the Returns Summary Box

--------------------------------------------------------------------------

Commercial Operating Statements According to Three Different Common Lease Types_Pierre Elie Mattijs_Sep-20-26.xlsx

A simple grid to understand how commercial operating statements are impacted based on three different common lease types: Triple Net (NNN), Full-Service Gross (FSG) and Modified Gross (MG).

--------------------------------------------------------------------------

Roll Calculations_Pierre Elie Mattijs_Sep-20-26.xlsx

A simple model that forecasts the monthly cash flow of a single commercial space through a lease expiration (roll), using probability-weighted assumptions for renewal, downtime, free rent, tenant improvements and leasing commissions.

Done in 00:26:43.
