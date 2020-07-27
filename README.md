# ZLOOKUP

Google Sheet Fuzzy String Matching Custom Function

# How to install the script

1. Create or open an existing spreadsheet in Google Sheets.
2. Select the menu item Tools > Script editor. If you are presented with a welcome screen, click Blank Project on the left to start a new project.
3. Delete any code in the script editor. Copy and paste the code from zlookup.gs into the script editor.
4. Select the menu item File > Save. Give the script project a name and click OK.
5. All done! Now you can use the custom function.

# How to use

Exactly the same as vlook up except the last parameter: accuracy score. Accuracy score must be number between 0 to 100.

=ZLOOKUP(search_key, range, index, accuracy_score)
