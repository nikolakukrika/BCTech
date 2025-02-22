# What is Business Central Data Analysis?
In the 2023 release wave 1 of Business Central, we are introducing a new powerful feature that allows you to analyze data on lists directly in the Business Central.

Read more about Data Analysis here: https://learn.microsoft.com/en-us/dynamics365/release-plan/2023wave1/smb/dynamics365-business-central/analyze-group-pivot-data-list-pages-using-multiple-tabs

# How can I use Data Analysis?
Data Analysis is meant for quick fact checking and ad-hoc analysis when you don't want to run a report, if a report for your specific needs does exist, or if you want to quickly iterate to get a good overview on part of your business.

In the following table, you'll find examples of usage scenarios for each main area in the Business Central application.

| Area    | Scenario | How Data Analysis can help | Data Foundation | Fields to get you started | Built-in report(s) | Try in Business Central (new in 2023w2) | 
| ------- | ---------| -------------------------- | --------------- | ------------------------- | ------------------ | ----- | 
| Finance (Accounts Receivables) | See what your customers owe you, maybe broken down into time intervals for when amounts are due. | Open the Customer Ledger Entries list and switch on Analyze. Go to the Columns menu and remove all columns (click the box next to the _Search_ field). Turn on _Pivot_ mode (located directly above the _Search_ field). Now, drag the _Customer Name_ field to the _Row Groups_ area and drag _Remaining Amount_ to the _Values_ area. Finally, find the _Due Date Month_ field and drag it to the _Column Labels_ area. If you want to restrict the analysis to a given year/quarter, apply a filter in the _Additional Filters_ menu (to the right, just below the _Columns_ menu.) Rename your analysis tab to "Aged Accounts by Month" or something that describes this analysis for you. | [Customer Ledger Entries](https://businesscentral.dynamics.com/?page=25) | _Customer Name_, _Due Date_, and _Remaining Amount_. | [Aged Accounts Receivables](https://businesscentral.dynamics.com/?report=120) </br></br> [Customer Statement](https://businesscentral.dynamics.com/?report=1316)  | [Click here to create](https://businesscentral.dynamics.com/do?page=25&dc=0&bookmark=C_FQAAAACHaBA#open-analysisview=H4sIAAAAAAAAA-2aW2_aMBTH3_kUftweQJCuF_HGyNp1Gi2CatKekOMcwFpiZ760RdO--0LWpjZB7TTWtTr4MSaJ-P3PxT7nRNAc-mTAmLTCaDIBBvyaJhlokqzISAqzbHE9tEqBMF843PSJURZaTGY2F1NDDfRbhLRJuXCe9slYasPFgsTlD-U6ITc8Ncs-6fWizmG1sOQp3L1kfVlwIaB8UNgsqxa0VGbj8lykcOus0cXi1ArmrCh5c6akLfpkTjMN3trm0wW_lsa9sVrYvGueOZdb8WYroMpljLpdZITfLVUGdoCkmr12xrzycWSEsWQ2LyOWXK0KjHFY813IjocXHWPAG1ptZA4KPV65-3ihd_SfvLN-8QZed3fPBM0ULwyX4kXIntdyZ5lMaEZiXgafLhFJjwxl6mcYHD7aII2wkv4-3LEVVr5LxRdclLYc5OtDrkd4iODEhhqLvPk8_PoWHVwMCTdYLefCIbXfUEGK14AeHVILTiCnXKyrwKYRo96JA-i-fgdCbfMXAzQdpFac0nWnqsl2gODcElvA2ka7R3uihfaPIm8XPEfgB7run6Ah7Z3VfE_0zZ603bPjbTVd7xG0MV1VPaXxevtjmxU8ktB7gCvrPTEvUQTDmGLG600v5roabGDNo01IpEOJJifS9LqFFOWAoubskCuZgaJlFkIfpZusyIO1gYs9ZhvAKEO37qc63GOpNU8yP3oxFGEPVfQ-0I7obac-Bte-jA7znnAEZilTtHOPArwC5ggHlSAfZZYiPCZ8EEatGhN_JGy3Rfl_ICVG1tF3yv0MisM_R6A1XcAadAKMFxw2ess4PgSo2d5T8e3u80GEOXS6LP8Os8b5DuAA636xhfXdHrEe7hHr0R6xHu8R6wlWVrponymetgfWyGH16bm3p762qdFfMVa3zrzRWNuftsyibhS1P1FhqVrNHptg-8Nd7IqcQqKCJJ4kI6rYMuhR6zEoFM-CHo5_hGhxUqoVEORw5MiCdzi5wy6sNkGQWpApFAbyBFTQpNbkkhkZFHEVuZDXwUl8SWJgQRJPkqDEnRIHoa5rKBLquoYkoa7z9Qh1nacHViWq30ey7mDOeWZA6T758bP1CyHp9VjDQgAA&zip=1&base64=1) (CTRL+click to open in a new browser tab) | 
| Finance (Income statement) | See your income over the income accounts from the chart of account, maybe broken down into time intervals for when amounts were posted. | Open the General Ledger Entries list and switch on Analyze. Go to the Columns menu and remove all columns (click the box next to the _Search_ field). Turn on _Pivot_ mode (located directly above the _Search_ field). Now, drag the _G/L Account No._ field to the _Row Groups_ area and drag _Amount_ to the _Values_ area. Finally, find the _Posting Date Month_ field and drag it to the _Column Labels_ area. For the income statement, you need to filter on the accounts you use for this, in the Business Central demo data, these are accounts starting with "4", your chart of account setup might be different (if you run the [Trial Balance by Period](https://businesscentral.dynamics.com/?report=38) report, you can easily see which accounts is used in your setup). Set a filter on appropriate accounts in the _Additional Filters_ menu (to the right, just below the _Columns_ menu.) Rename your analysis tab to "Income by Month" or something that describes this analysis for you. | [General Ledger Entries](https://businesscentral.dynamics.com/?page=20) | _G/L Account No._, _Posting Date_, and _Amount_. | [Trial Balance by Period](https://businesscentral.dynamics.com/?report=38)  | [Click here to create](https://businesscentral.dynamics.com/do?page=20&dc=0&bookmark=C_EQAAAACHcRA#open-analysisview=H4sIAAAAAAAAA-2aTY_aMBCG7_wKa-9QCPtR5cbCLqIq20pbtUdkHAOWHDu1xwv8-yaGBhMoVFSsqPEx44_4ecd2ZhwLnNIYDQSRKUUaMNCUCkDjJRpKAbMa012jVG76zug8RqAMrRHJTSpei8pxDaE6yg2DJEZfpQYmpqiXF-R2hOYsgVmMWq2ocWcNM5bkb5tgrlcVMiYEzVsKw7k1aKmg8jgQCV04NjydPhtBHIuS876SJnN7_m2rts7Ym4TtIeSGaq0Jdx738o2WFCsXMmo2LwvRuqpK2PxbvJ8GK6AHCJ3u9wJiTS7dhamd4af78OyIe13YOoDXk8TY9fttmXm5BEvAF9nY4osevODrf_iMOoRIcxzx2AI8mbDsuALY_HfvUU0Uy4BJsbXs7v2YnH0ux5ijHstnqM4ZUQt1ZUIPOdEb1MhfVCoa5XfD133VQj4avSG1r_DXn0omV8DaSYsvyRZZ-wxc2qTvGwXQMYOjcGf7QJ4Xrqto4i_dI-aNMsLxdTfdgvQ0Un0SoJY7cJ448GmR576iCHD-lG94Avo6y4dDDDiRXPtoJPefbj17WG-viPXuiljvr4j14YpYP_rKiqf1vmJJvWNAdu3xugt5cWfLJzHaqqOdQ_T67pnsKGpGUf0TFgar5eidkpiL1-OZjlUQxBFkiBWZBTXWanQyxXhQo5wbYZ2UG6kRNIhRisHDzCj3DDM1GoIcazleaQY0HVMVFFkr8oWADHps9HiRb2GCuIL0KAmCOIIEHawO7ZC9VfQI2VtFkJC9uWqE7M1Rwy8dbPlQlqeTE8aBKl1cna1c94pXTW158W80RqnhwBxr0Q3Xq3qFvm5doAtYFyAE1qQBK9A_2Pqa46afGN3c3pS92GH-AvmeVg4KLAAA&zip=1&base64=1) (CTRL+click to open in a new browser tab) | 
| Finance (total assets) | See your assets over the asset accounts from the chart of account, maybe broken down into time intervals for when amounts were posted. | Open the General Ledger Entries list and switch on Analyze. Go to the Columns menu and remove all columns (click the box next to the _Search_ field). Turn on _Pivot_ mode (located directly above the _Search_ field). Now, drag the _G/L Account No._ field to the _Row Groups_ area and drag _Amount_ to the _Values_ area. Finally, find the _Posting Date Month_ field and drag it to the _Column Labels_ area. For the assets statement, you need to filter on the accounts you use for this, in the Business Central demo data, these are accounts starting with "10", your chart of account setup might be different (if you run the [Trial Balance by Period](https://businesscentral.dynamics.com/?report=38) report, you can easily see which accounts is used in your setup). Set a filter on appropriate accounts in the _Additional Filters_ menu (to the right, just below the _Columns_ menu.) Rename your analysis tab to "Income by Month" or something that describes this analysis for you. | [General Ledger Entries](https://businesscentral.dynamics.com/?page=20) | _G/L Account No._, _Posting Date_, and _Amount_. | [Trial Balance by Period](https://businesscentral.dynamics.com/?report=38)  |
| Sales | Get an overview of the customers that purchase the most or that owe the most. | Open the _Customer Ledger Entries_ list and switch on Analyze. Go to the Columns menu and remove all columns (click the box next to the _Search_ field). Now, drag the _Customer Name_ field to the _Row Groups_ area and then the _Document No._ field below it. Then drag the fields _Sales_ and _Remaining Amount_ to the _Values_ area. | [Customer Ledger Entries](https://businesscentral.dynamics.com/?page=25) | _Customer Name_, _Document No._, _Sales_, and _Remaining Amount_. | [Customer - Top 10 list](https://businesscentral.dynamics.com/?report=111) |
| Sales | Analyse your expected sales volume. </br></br> See order details with the sales amount for orders not yet shipped broken down to customer and year/month. | Open the _Sales Orders_ list and switch on Analyze. Go to the Columns menu and remove all columns (click the box next to the _Search_ field). Turn on _Pivot_ mode (located directly above the _Search_ field). Now, drag the fields _Sell-to Customer Name_, _Sell-to Customer No._, and _No._ fields to the _Row Groups_ area (in that order). Then drag the field _Amount_ to the _Values_ area. Finally, find the _Document Date Year_ and _Document Date Month_ fields and drag them to the _Column Labels_ area (in that order).| [Sales Orders](https://businesscentral.dynamics.com/?page=9305) | _Sell-to Customer Name_, _Sell-to Customer No._, _No._ , _Amount_, _Document Date Year_ and _Document Date Month_. | [Customer - Order Summary](https://businesscentral.dynamics.com/?report=107) |
| Sales | Analyse your expected sales by (ship-to) country. </br></br> See order details with the sales amount for orders not yet shipped broken down to ship-to country and customer. | Open the _Sales Orders_ list and add the field _Ship-to Country/Region_ using personalization (in the very top menu to the right, go to Settings, Personlize). Exit personalization mode. Now switch on Analyze. Go to the Columns menu and remove all columns (click the box next to the _Search_ field). Turn on _Pivot_ mode (located directly above the _Search_ field). Now, drag the fields _Ship-to Country/Region_, _Sell-to Customer Name_ and _Sell-to Customer No._ fields to the _Row Groups_ area (in that order). Then drag the field _Amount_ to the _Values_ area. Finally, find the _Document Date Year_ and _Document Date Month_ fields and drag them to the _Column Labels_ area (in that order).| [Sales Orders](https://businesscentral.dynamics.com/?page=9305) | _Ship-to Country/Region_, _Sell-to Customer Name_, _Sell-to Customer No._, , _Amount_, _Document Date Year_ and _Document Date Month_. | [Customer - Order Summary](https://businesscentral.dynamics.com/?report=107) |
| Sales | Find your top sales people.</br></br>Calculate bonus for salespersons based on what have been invoiced. </br></br> If bonus calculation should exclude returned items, then use _Customer Ledger Entries_ as the data source instead. | Open the _Posted Sales Invoices_ list, add fields _Posting Date_ and _Customer Group_ using personalization (in the very top menu to the right, go to Settings, Personlize). Exit personalization mode. Now switch on Analyze. Go to the Columns menu and remove all columns (click the box next to the _Search_ field). Turn on _Pivot_ mode (located directly above the _Search_ field). Now, drag the fields _Salesperson Code_, _Customergroup Code_, and _Customer Name_ fields to the _Row Groups_ area (in that order). Then drag the field _Amount_ to the _Values_ area. Finally, find the _Posting Date Year_ and _Posting Date Quarter_ fields and drag them to the _Column Labels_ area (in that order).| [Posted Sales Invoices](https://businesscentral.dynamics.com/?page=143) | _Salesperson Code_, _Customergroup Code_, _Customer Name_,  _Amount_, _Posting Date Year_ and _Posting Date Quarter_ | N/A |
| Sales | Get an overview on your sales. | Open the _Sales Lines_ list and switch on Analyze. Go to the Columns menu and remove all columns (click the box next to the _Search_ field). Set filters on _Type_ = Item, _Doc Type_ = Order and Invoice and _Outstanding Qty_ > 0. Turn on _Pivot_ mode (located directly above the _Search_ field). Now, drag the fields _Location_, _Shipment Date Month_, _Shipment Date_, _Item Number_, and _Document Number_ to the _Row Groups_ area (in that order). Then drag the field _Amount_ to the _Values_ area. | [Sales Lines](https://businesscentral.dynamics.com/?page=XXX) | _Type_, _Doc Type_, _Outstanding Qty_, _Location_, _Shipment Date Month_, _Shipment Date_, _Item Number_, and _Document Number_ | N/A |
| Purchasing | Create a Goods Received, Not Invoiced (GRNI) overview. | Open the _Purchase Line_ list, add the field _Amount Received Not Invoiced_ using personalization (in the very top menu to the right, go to Settings, Personlize). Exit personalization mode. Now switch on Analyze. Go to the Columns menu and remove all columns (click the box next to the _Search_ field). Set filters on _Type_ = Item, and _Amt. Rec. Not Invoiced (LCY)_ > 0. Now, drag the fields _Vendor No._, _Document No._, and _No._ (which is the item number)_ fields to the _Row Groups_ area (in that order). Finally, add _Amt. Rec. Not Invoiced (LCY)_ to include it on the overview. [Purchase Line](https://businesscentral.dynamics.com/?page=TODO) | _Vendor No._, _Document No._, _No._, and _Amt. Rec. Not Invoiced (LCY)_ | N/A |
| Finance (Accounts Payable) </br></br>Purchasing | See what you owe your vendors, maybe broken down into time intervals for when amounts are due. | Open the _Vendor Ledger Entries_ list and switch on Analyze. Go to the Columns menu and remove all columns (click the box next to the _Search_ field). Turn on _Pivot_ mode (located directly above the _Search_ field). Now, drag the fields _Vendor Name_, _Document Type, and _Document No._ fields to the _Row Groups_ area (in that order). Then drag the field _Remaining Amount_ to the _Values_ area. Finally, find the _Due Date Year_ and _Due Date Month_ fields and drag them to the _Column Labels_ area (in that order).| [Vendor Ledger Entries](https://businesscentral.dynamics.com/?page=29) | _Vendor Name_, _Document Type, _Document No._, _Remaining Amount_, _Due Date Year_ and _Due Date Month_. |   [Vendor - Balance to Date](https://businesscentral.dynamics.com/?report=321) </br></br> [Vendor - Top 10 list](https://businesscentral.dynamics.com/?report=311) |
| Compliance: who changed what data when | See who changed what sensitive data or what data was changed by whom. | Open the _Change Log Entries_ list and switch on Analyze. Go to the Columns menu and remove all columns (click the box next to the _Search_ field). </br></br> To analyze **Who did What When**, drag the field _User ID_ (who did it) to the _Row Groups_ area. Now click the fields _Date and Time_ (when did it happen), _Table Caption_ (on what table), _Field Caption_ (on which field), _Primary Key Value 2_ (typically a code field), _Primary Key Value 3_ (typically the company name), _Type of Change_ (Insert/Update/Delete), _Old Value_, _New Value_.</br></br> To analyze **Data Changes by table/field**, drag the fields _Table Caption_ (on what table), _Field Caption_ (on which field) to the _Row Groups_ area (and click the fields above, including the _User ID_ field). | [Change Log Entries](https://businesscentral.dynamics.com/?page=595) | _User ID_ (who did it), _Date and Time_ (when did it happen), _Table Caption_ (on what table), _Field Caption_ (on which field), _Primary Key Value 2_ (typically a code field), _Primary Key Value 3_ (typically the company name), _Type of Change_ (Insert/Update/Delete), _Old Value_, and _New Value_. |  N/A  |
| Compliance: License overview by user | Get an overview over which users are enabled/disabled and which license they have been assigned. | Open the _Users_ list and switch on Analyze. Go to the Columns menu and remove all columns (click the box next to the _Search_ field). Drag the fields _Status_ (user enabled/disabled) and _License Type_ to the _Row Groups_ area (and click the fields _User Name_, _Full Name_ and _Authorization email_). | [Users](https://businesscentral.dynamics.com/?page=9800) |  _Status_, _License Type_, _User Name_, _Full Name_ and _Authorization email_ |  N/A  |
| Inventory (track returns by return reason and month) | Get an overview of goods that customers return, broken down on the return reason. Use this for your quality control processes. | Open the _Item Ledger Entries_ list, add the field _Return Reason Code_ using personalization (in the very top menu to the right, go to Settings, Personlize). Exit personalization mode. Now switch on Analyze. Go to the Columns menu and remove all columns (click the box next to the _Search_ field). Drag the fields _Return Reason Code_, and _Posting Date Month_ to the _Row Groups_ area (in that order). Then drag the fields _Quantity_ and _Cost Amount_ to the _Values_ area. Finally, pick any other fields that you want in the analysis, and enable them in the Columns area. In this example, we enable _Posting Date_, _Document Type_, _Item No._, and  _Document No._ | [Item Ledger Entries](https://businesscentral.dynamics.com/?page=38) | _Return Reason Code_, _Posting Date Month_, _Quantity_ , _Cost Amount_, _Posting Date_, _Document Type_, _Item No._, and  _Document No._ . |  |
| Inventory (track inventory movements) | Get an overview of how goods in your inventory move between locations | Open the _Item Ledger Entries_ list and switch on Analyze. Go to the Columns menu and remove all columns (click the box next to the _Search_ field). Drag the field _Location Code_ to the _Row Groups_ area. Then drag the field _Quantity_ to the _Values_ area. Finally, pick any other fields that you want in the analysis, and enable them in the Columns area. In this example, we enable _Posting Date_, _Item No._, and  _Entry No._ | [Item Ledger Entries](https://businesscentral.dynamics.com/?page=38) | _Location Code_, _Quantity_, _Posting Date_, _Item No._, and  _Entry No._ |  |
| Inventory (track "old" stock) | Get an overview of items in your inventory that have been on stock for long and is not selling well. | Open the _Item Ledger Entries_ list and switch on Analyze. Go to the Columns menu and remove all columns (click the box next to the _Search_ field). Drag the fields _Posting Date Year_, _Posting Date Month_, and _Item No._ to the _Row Groups_ area. Then enable the fields _Posting Date_, _Entry type_, _Quantity_ and _Remaining Quantity_ in the Columns area (just pick them). Set a 'Less than' filter on _Posting Date_ to define "old".  | [Item Ledger Entries](https://businesscentral.dynamics.com/?page=38) | _Posting Date Year_, _Posting Date Month_, _Item No._, _Posting Date_, _Entry type_, _Quantity_, and _Remaining Quantity_. |  |
| Inventory (input/output) | Get an overview of purchases/sales in your inventory by Month (or Quarter.) | Open the _Item Ledger Entries_ list and switch on Analyze. Go to the Columns menu and remove all columns (click the box next to the _Search_ field). Turn on _Pivot_ mode (located directly above the _Search_ field). Now drag the fields _Posting Date Year_, _Posting Date Month_, and _Item No._ to the _Row Groups_ area. Then drag the fields _Quantity_ and _Sales Amount_ to the _Values_ area. Save this analysis as _Sales by Month_. Now copy this analysis (choose Duplicate in the Analysis menu) and change the field _Sales Amount_ to _Cost Amount (Actual)_ in the _Values_ area. Save this analysis as _Purchases by Month_.  | [Item Ledger Entries](https://businesscentral.dynamics.com/?page=38) | _Posting Date Year_, _Posting Date Month_, _Item No._, _Quantity_, _Sales Amount (actual)_, and _Cost Amount_. |  |


# What Power Point presentations are available?
To make it easier to adopt Data Analysis for Business Central, we added a number of Power Point presentations that you can use for various situations.

| Your role is... | You want to... | Use this deck (click and then download) |
| --------------- | ---------------| ------------- |
| analyze data all over the business | Present a few killer-scenarios to your colleagues | [Analysis scenarios.pptx](<./decks/Analysis scenarios.pptx>) |
| as a trainer | Help partners/customers/colleagues get started with Data Analysis (maybe do a lunch session or present at a conference) | [Analyze Data on list pages.pptx](<./decks/Analyze Data on list pages.pptx>) |


# Disclaimer
Microsoft Corporation (“Microsoft”) grants you a nonexclusive, perpetual, royalty-free right to use and modify the software code provided by us for the purposes of illustration  ("Sample Code") and to reproduce and distribute the object code form of the Sample Code, provided that you agree: (i) to not use our name, logo, or trademarks to market your software product in which the Sample Code is embedded; (ii) to include a valid copyright notice on your software product in which the Sample Code is embedded; and (iii) to indemnify, hold harmless, and defend us and our suppliers from and against any claims or lawsuits, whether in an action of contract, tort or otherwise, including attorneys’ fees, that arise or result from the use or distribution of the Sample Code or the use or other dealings in the Sample Code. Unless applicable law gives you more rights, Microsoft reserves all other rights not expressly granted herein, whether by implication, estoppel or otherwise. 

THE SAMPLE CODE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL MICROSOFT OR ITS LICENSORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THE SAMPLE CODE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.