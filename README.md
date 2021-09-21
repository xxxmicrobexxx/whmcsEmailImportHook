# whmcsEmailImportHook
WHMCS hook to display the failed email import log below the list of support tickets

copy the code to /includes/hooks/recentFailedEmails.php (or any name.php you like in that directory)

Now when you view the list of support tickets, at the bottom will be a list of recent failed imported emails so you can check for false positives.  Click the subject to pop up the email contents.

This list is the same as you would see in the Support Ticket Mail Import Log, filtered to only show fails.
