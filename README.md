# SolutionsOTP
Simple website to generate OTP codes.  Shamelessly adapted from the work of https://github.com/gbraad/gauth

This was created to be embedded as a tab inside of Microsoft Teams, and allow many team members to share MFA codes.  All buttons have been removed from the user interface, adding MFA accounts needs to be done by editing gauth.js.

For bonus points, host it using Azure websites, and use conditional access policies to restrict access to employees with AzureAD accounts.

https://solutionsotplab.azurewebsites.net/
