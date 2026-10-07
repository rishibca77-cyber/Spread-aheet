# Phase 7: Test with Changed Data

## Steps
1. Edit your spreadsheet:
   - Change one person's email.
   - Change another person's name.
   - Add two new employees.
   - Leave the other rows the same.
2. Download it again as `.xlsx`.
3. Go to All > System Import Sets > Load Data.
4. Choose the existing import table **Staff Import**, pick the file, sheet 1, header row 1, then click **Submit**.
5. Click **Run Transform**, select **Staff Spreadsheet Load**, and click **Transform**.
6. Open **Transform History** and check the counts: 2 inserted and 2 updated.
7. Open **Staff Directory** to confirm the changes.
8. Repeat the import with the same file. Nothing is inserted or updated this time, and the rows are ignored.

## Video narration
"I upload a modified sheet. Changed rows are updated, new rows are inserted, and uploading the same file again changes nothing, which proves Coalesce works."

## Result
Proof that Coalesce updates existing records and only adds new ones.
