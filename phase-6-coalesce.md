# Phase 6: Enable Coalesce to Prevent Duplicates

## Steps
1. Go to All > System Import Sets > Transform Maps.
2. Open **Staff Spreadsheet Load**.
3. In the **Field Maps** related list, open the **Employee ID** mapping.
4. Set **Coalesce** to **true**.
5. Click **Save/Update**.

## Video narration
"In real projects the same data gets imported many times. Coalesce on Employee ID makes ServiceNow update an existing record instead of creating a duplicate."

## Result
Re-importing a record with the same Employee ID updates it instead of adding a copy.
