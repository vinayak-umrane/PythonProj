# PythonProj
Using this Python Code, you can track your Mutual Fund Investments (Both Monthly SIP and Lumpsum) realtime in excel file.

Excel File Name: MutualFundInvestmentTracker.xlsx

In this xlsx file there are 5 different Sheets. Sheet names are as below:
1. Input_SIP_Investment
2. Input_LumpSum_Investment
3. Output_SIP_Investment
4. Output_LumpSum_Investment
5. Summary

Step-1: Download attached MutualFundInvestmentTracker.xlsx file to your local machine.
Step-2: In "Input_SIP_Investment" sheet, update records for your SIP investments. As a Input, you just need to feed in below details for all your SIP Investment.

MF Scheme Code	
Monthly SIP Deduction Date (In DD Format)	
Monthly SIP Amount	
Total Units	
Unit Calculation Date	
Total Invested Amount

Note: You can get the "MF Scheme Code" from https://www.amfiindia.com/spages/NAVOpen.txt 
You just need to search your fund name in above url and copy the scheme code from 1st column into "MF Scheme Code" column in your input "Input_SIP_Investment" sheet.

Step-3: In "Input_LumpSum_Investment" sheet, update records for your Lumpsum Mutual Fund investments. As a Input, you just need to feed in below details.

Scheme Code	
Total Invested Amount	
Total Units

Thats all....it will automatically calculate current value of your Mutual Fund Investments (Both Monthly SIP and Lumpsum) realtime and update details in "Output_SIP_Investment" and "Output_LumpSum_Investment" sheets and finally update the summary with total invested amount, total current value and ProfitAndLoss (PnL) in "Summary" Sheet.
