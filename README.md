# Exercise-2-Batch-and-Scheduled-Jobs

Use Case
Once a month, all Accounts should receive an email containing the Amounts of Closed Won/Open/Closed Lost Opportunities that were created/updated in the corresponding month.

Requirements
1.  Create a batch class that summarizes all Opportunity Amounts for each Account;

2.  An email should be sent to the primary contact of all Accounts, containing a table with the Closed Won/Open/Closed Lost summarized Opportunity Amounts;

3.  The schedulable class that calls the batch class should be created;

4.  The class should be scheduled from the Developer Console. Please provide the script to schedule the job daily at 10:00 AM, once a week (Friday at 1:00 PM), once a month(Last Friday of the Month at 6:00 PM).
