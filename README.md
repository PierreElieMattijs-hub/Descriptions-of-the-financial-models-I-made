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

(GitHub Published) Three Operating Statements Models_Pierre Elie Mattijs_Sep-25-26.xlsx

A simple grid to understand how commercial operating statements are impacted based on three different common lease types: Triple Net (NNN), Full-Service Gross (FSG) and Modified Gross (MG).

Done in 00:12:42.

--------------------------------------------------------------------------

(GitHub Published) Roll Calculations_Pierre Elie Mattijs_Sep-25-26.xlsx

A simple model that forecasts the monthly cash flow of a single commercial space through a lease expiration (roll), using probability-weighted assumptions for renewal, downtime, free rent, tenant improvements and leasing commissions.

Done in 00:26:43.

--------------------------------------------------------------------------

(GitHub Published) Simple Waterfall_Pierre Elie Mattijs_Sep-25-26.xlsx

A simple two-partner waterfall based on an 20/80 split between GP and LP. There is first 25% return-on-equity hurdle for the two partners. Then, a 50/50 split of the remaining cash flow. At the end, I add a small returns hurdle box.

Done in 00:14:11.

-------------------------------------------------------------------------

(GitHub Published) Waterfall Intermediate_Pierre Elie Mattijs_Sep-29-26.xlsx

A three-tier waterfall based on an 85/15 split between LP and GP, over a five-year project cash flow. There is first an 8% IRR hurdle, pari passu, where both partners get their capital back. Then, a 70/30 split until the LP reaches a 10% IRR, and a 65/35 split for the rest. Each hurdle has its own accrual account per partner and an IRR check. At the end, I sum up the cash flows of both partners and reconcile them with the deal-level cash flow.

Done in 00:40:05.

-------------------------------------------------------------------------

(GitHub Published) Simple Multifamily Underwriting_Pierre Elie Mattijs_Oct-4-26.xlsx

In this multifamily underwriting case, I am provided with an offering memorandum (OM) from a broker - document Sherwood Package OM-Adjusted attched -, the investment firm’s pro-forma model to populate with the relevant data, as well as the historical financials already included in the pro-forma model. 
My task is to underwrite the property by first extracting information from the OM, then analyzing the historical financials, and finally forecasting cash flows.

Step 1 00:01:45

Sheet Assumptions: 
- Completed the basic operating assumptions from rows 6-20
- Added the acquisition date

Step 2 00:04:53

Sheet Unit Mix: 
- Completed the entire Unit Mix tab using the market rents provided by the broker in the OM. 
Note: As I am still getting familiar with this pro forma, I traced formula dependencies to understand how the tabs in the model are linked. I Used an LLM to compare the OM and my Excel pro forma. All displayed figures matched.

Step 3 00:05:07

Sheet Assumptions: 
- Completed two other operating assumptions: Other Income per Unit per Year and RUBS Income per Unit per Year. Let's pretend I received these assumptions from a supervisor.
Note: Other Income and RUBS Income on the Pro-Forma and Returns sheet depend on these operating assumptions. These income items are projected on that sheet.

Step 4 00:06:09

Sheet Assumptions: 
- Filled in two additional operating assumptions: Loss-to-Lease and Vacancy Rate.
Note: I entered a fixed percentage for Loss-to-Lease, which seems unrealistic. However, I will keep it as is while acknowledging this 'limitation'. The Vacancy Rate is also fixed. A constant percentage is more common for Vacancy Rate than for Loss-to-Lease.
Once again, I will pretend I received these assumptions from a supervisor. They will be cross-checked later against the historical financials.

Pro-Forma and Returns sheet :
- Completed Concessions and Non-Rev/Bad Debt/Adjust.
Note: I have now completed the forecast down to Net Rental Income, except for the Gain with Renovations row, as I have not reached that section yet.

Step 5 00:12:02

T-12 Backup sheet:
- Created data validation dropdown lists using the revenue and expense itens from the Pro-Forma and Returns tab. I then assigned each T-12 line an item. 
Note: these labels will then be used in SUMIFS formulas to aggregate the amounts into the appropriate rows on the Pro-Forma and Returns sheet.

Step 6 00:22:58

Pro-Forma and Returns sheet:
- Used SUMIF formulas to aggregate the T-12 expenses by category in a temporary calculation area, starting in column T.
- Divided each total by the number of units to calculate annual expenses per unit in column U, then increased these amounts by 3% in column V.
- Pasted the resulting values from column V into the pro forma’s per-unit expense inputs in column D. The model multiplies these inputs by the number of units to calculate total projected expenses.
- Also used SUMIF formulas to aggregate historical revenues and compare them with my forecast assumptions.
- Reversed the sign of historical RUBS to present it as income rather than a reduction in expenses.
Note: This comparison helps me assess whether my assumptions are reasonable relative to historical performance.

Step 7 00:26:45

Pro-Forma and Returns sheet:
- Completed the growth and vacancy assumptions for two scenarios: Continued Expansion and Market Downturn and Recovery. 
Note: The operating scenario toggle in the Assumptions sheet selects which scenario is used in the cash flow forecast. Kept the additional Loss-to-Lease adjustment at 0% in both scenarios, as the initial 2% assumption is already included in the pro forma. Let's pretend all assumptions come from market research.  

Step 8 00:27:14

Sheet Assumptions:
- Entered CapEx per Unit per Yr.

Pro-Forma and Returns sheet:
- Added annual renovation income from Year 3 on row 32, growing thereafter.
Note: The model unusually assumes ongoing CapEx throughout the holding period and renovation income starting all at once in Year 3.

Step 9 00:29:28

Sheet Assumptions:
- Completed Acquisition Assumptions and Exit Assumptions boxes.
