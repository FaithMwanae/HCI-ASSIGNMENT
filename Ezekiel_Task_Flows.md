**TASK FLOWS**

**Student Lost-and-Found Mobile App**

Prepared by: Ezekiel  
Role: Task Flows & User Journeys

# 1\. Task Flow - Report a Lost Item

Goal: Allow a student to report an item that they have lost.

START  
↓  
Open App  
↓  
Home Screen  
↓  
Tap "Report Lost Item"  
↓  
Lost Item Form  
↓  
Enter Item Name  
↓  
Enter Item Description  
↓  
Enter Location Lost  
↓  
Enter Date Lost  
↓  
Add Image  
↓  
Review Details  
↓  
Tap "Submit"  
↓  
Confirmation Message  
↓  
Lost Item Successfully Reported  
↓  
END

Expected Outcome: The lost item is successfully registered in the application.

# 2\. Task Flow - Search and Claim a Lost Item

Goal: Allow a student to search for an item that may have been found and submit a claim.

START  
↓  
Open App  
↓  
Home Screen  
↓  
Tap "Search Items"  
↓  
Search Screen  
↓  
Enter Item Name  
↓  
Apply Filters  
↓  
View Search Results  
↓  
Select Possible Matching Item  
↓  
View Item Details  
↓  
Is This My Item?  
↓  
YES  
↓  
Submit Claim  
↓  
Claim Confirmation  
↓  
Track Claim Status  
↓  
END

If the item is not a match: View Item Details → Not My Item → Return to Search Results → Search Again.  
<br/>Expected Outcome: The student identifies a possible matching item and successfully submits and tracks a claim.

# 3\. Task Flow - Report a Found Item

Goal: Allow a student who has found an item to report it.

START  
↓  
Open App  
↓  
Home Screen  
↓  
Tap "Report Found Item"  
↓  
Found Item Form  
↓  
Enter Item Name  
↓  
Enter Description  
↓  
Enter Location Found  
↓  
Enter Date Found  
↓  
Add Image  
↓  
Review Details  
↓  
Tap "Submit"  
↓  
Confirmation Message  
↓  
Found Item Successfully Reported  
↓  
END

Expected Outcome: The found item is added to the system so that its owner can search for it and submit a claim.

# 4\. Main Interaction Flow

LOGIN  
↓  
HOME  
<br/>HOME → Report Lost Item → Enter Details → Add Image → Review & Submit → Confirmation  
<br/>HOME → Report Found Item → Enter Details → Add Image → Review & Submit → Confirmation  
<br/>HOME → Search Items → Search & Filter → Search Results → Item Details → Submit Claim → Track Claim

# 5\. Three Complete User Scenarios

## Scenario 1: Reporting a Lost Phone

1. The student opens the Lost-and-Found mobile application.
2. The student selects "Report Lost Item".
3. The student enters the item name.
4. The student enters a description of the phone.
5. The student enters the location where the phone was lost.
6. The student enters the date the phone was lost.
7. The student adds an image of the phone.
8. The student reviews the information.
9. The student selects "Submit".
10. The application displays a confirmation message.

Successful outcome: The lost phone is successfully reported.

## Scenario 2: Searching and Claiming a Lost Item

1. The student opens the application.
2. The student selects "Search Items".
3. The student enters the phone name or keyword.
4. The student applies an appropriate filter.
5. The application displays matching found items.
6. The student selects a possible matching item.
7. The student views the item details.
8. The student determines that the item matches their lost phone.
9. The student selects "Submit Claim".
10. The application confirms that the claim has been submitted.
11. The student checks "Claim Status".

Successful outcome: The student successfully submits and tracks a claim.

## Scenario 3: Reporting a Found Item

1. The student opens the application.
2. The student selects "Report Found Item".
3. The student enters the item name: "Black Wallet".
4. The student enters a description.
5. The student enters the location where the wallet was found.
6. The student enters the date it was found.
7. The student adds an image.
8. The student reviews the information.
9. The student selects "Submit".
10. The application displays a confirmation message.

Successful outcome: The found wallet is successfully reported and becomes available for searching.

# 6\. Screens Supporting the Task Flows

1. Login
2. Home
3. Report Lost Item
4. Lost Item Details
5. Add Image
6. Review Lost Item
7. Lost Item Confirmation
8. Report Found Item
9. Found Item Details
10. Review Found Item
11. Found Item Confirmation
12. Search Items
13. Search Results
14. Item Details
15. Submit Claim
16. Claim Confirmation
17. Claim Status