# ZLOOKUP

Google Sheet Fuzzy String Matching Custom Function. The script use the Levenshtein distance implementation for javascript from https://gist.github.com/andrei-m/982927/0efdf215b00e5d34c90fdc354639f87ddc3bd0a5 with a little bit of modification to calculate the accuracy score instead of distance.

# How to install the script

1. Create or open an existing spreadsheet in Google Sheets.
2. Select the menu item Tools > Script editor. If you are presented with a welcome screen, click Blank Project on the left to start a new project.
3. Delete any code in the script editor. Copy and paste the code from zlookup.gs into the script editor.
4. Select the menu item File > Save. Give the script project a name and click OK.
5. All done! Now you can use the custom function.

# How to use

Exactly the same as vlook up except the last parameter: accuracy score. Accuracy score must be number between 0 to 100.

=ZLOOKUP(search_key, range, index, accuracy_score)
