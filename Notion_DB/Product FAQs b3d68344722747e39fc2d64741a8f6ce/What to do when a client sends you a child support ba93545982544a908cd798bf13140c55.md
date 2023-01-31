# What to do when a client sends you a child support order?

Date Created: January 30, 2023 10:09 AM
Last Updated: January 30, 2023 11:17 AM

Where are the steps to do when a client sends in a CSUP order:

1. Look to see if they have the full garnishment service. If they do, the garnishment team wants us to send the orders to them and not handle them ourselves. If they do not have the full garnishment service, proceed with the below steps. Note that it does not matter if they have the ChildEFT service or not. This is a service we do not charge for so it can just be added.
Typically the Account Managers would not setup any CSUP unless we are helping the garnishment team. Clients have to pay for the Full Garn service if they want us to setup the deductions. Otherwise we should only setup the Agency code, when needed.

We should know how these generally get setup though so we can walk the client through it, if needed.

1. Save a copy of the order in the ClntData > Garnishments folder.
2. Review the order to see which CSUP agency it is for. Look at the Company Setup to confirm if the agency is already setup and properly. Company Setup > Deductions > Agency
a.	If the agency code is not already setup, go into the KB under Policies & Procedures to find the State Specific Setup Guide. Go to the applicable state tab and the CSUP EFT setup instructions are at the bottom of the tab.
b.	Note the instructions do not say a Payroll Group is needed but it must be “Active”.
c.	IMPORTANT: Some clients want a separate agency ID for each employee, even though employees may have the same CSUP agency. This is a really good idea so that if there is a mistake on one employee deduction it won’t mess up the agency payments for all employees with that CSUP agency.
3. Go to the applicable employee under Employee > Paycheck Data > Deductions and look to see if they already have any CSUP deductions already setup. Each CSUP deduction code (CS1, CS2, etc.) should only be used once. If they already have a CS1 then you must use CS2.
a.	When an employee does have more than one active CS deduction, the system automatically knows how to pro-rate the deductions appropriately when an employee doesn’t make enough pay to cover them all fully. It will pro-rate the deductions and the total of all CSUP deductions will stay within the maximum percent of disposable wages as long as the appropriate Calc Code is setup on each CS deduction (CH50, CH55, CH60 or CH65).
b.	If an employee has a regular garnishment or levy PLUS child support, a custom calc code is most likely needed on the garnishment/levy.
4. Setting up the CS deduction:
a.	Click Add > Select applicable CSUP deduction code (CS1, CS2, etc.) – don’t allow any of the CS deduction codes to be active as more than one record.
b.	Click “Continue”.
c.	Fill in the Rate/Amount based on the order and the appropriate pay freq (can look at the employee’s Pay Rates tab to see the pay freq).
d.	Look for the maximum % of disposable income to use and fill in the applicable calc code of CH50, CH55, CH60 or CH65.
i.	Also look on the prior page to see if the employee is in “Arrears greater than 12 weeks”.
ii.	If the maximum percentage is clearly listed then that is what you would use. However, if the maximum percentage shows as 50% or 60% but the “Arrears greater than 12 weeks” IS checked, then 5% needs to be added to make the needed calc code either CH55 or CH65.
iii.	If the maximum percentage is blank or just says “between 50-65%” but does not clearly list which it should be, then use 50% (or 55% if the arrears box is checked). Let the client know that the maximum percentage was not clearly listed so you picked one but they should confirm with the agency.
e.	Fill in the appropriate agency code.
f.	Misc Info – fill in the Remittance ID. If that is missing, fill in the Case ID and Order ID separated with a semi-colon.
g.	Notes – It’s a good idea to click on the “Notes” tab within that deduction and write out the names of the children and their birthdays and any case/order ID numbers. This can be helpful in the future if the employee has multiple orders and an agency sends an amended order with the identifying numbers missing.
h.	Save.