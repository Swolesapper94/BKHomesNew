# BKHomesNew
data aggregator/skiptracer

Calendar Site: https://www.pinellas.realforeclose.com/index.cfm?ZACTION=USER&ZMETHOD=CALENDAR
Auction Site (9/17/2024 for example): https://www.pinellas.realforeclose.com/index.cfm?zaction=AUCTION&zmethod=DAYLIST&AuctionDate=09/19/2024

Phase I
The desired intent of this script is to go on "Calendar Site" website populate 3 fields of information in a .csv. The script would need to open up the "Calendar Site" and then open up the "Auction Site"
    Auction Status
    Final Judgement Amount
    Property Address
The output will order the auctions in order of auction date, soonest to latest.
THe script will save in a .csv named 'Test_BKHomes'

Phase II
The script will loop through each calendar day on the "Calendar Site" and pull the above information.
The script will update the spreadsheet with the Active Auctions and skip the rest. Once it reached the end of the calendar, it will go into the next month, and so forth.
This script will be ran every morning at 0800ET and will save with the same name as the input file (Test_BKHomes). 

 