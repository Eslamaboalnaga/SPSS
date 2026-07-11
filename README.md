SPSS Sample Dataset - Placeholder Data

This is a SYNTHETIC/PLACEHOLDER dataset created to let you build and test your
Excel + Orange Data Mining workflow before your real student data is available.

Structure:
- 40 fictional students, evenly split across all 4 risk categories (10 each):
  RED (fails both), YELLOW (fails academic only or attendance only - 20 total), GREEN (passes both)

Thresholds used (as defined in the project):
- Academic Threshold: Average of Test 1-3 < 60% => FAIL
- Attendance Threshold: Attendance % < 75% => FAIL

Columns F (Average), H (Academic Status), I (Attendance Status), and J (Risk Category)
are all LIVE FORMULAS - if you replace columns C:E and G with real data, everything
recalculates automatically.

TO REPLACE WITH REAL DATA:
1. Keep the header row and column structure exactly as-is.
2. Overwrite Student ID, Name, Test 1-3, and Attendance % with real values.
3. Do not touch columns F, H, I, J - they will auto-update.
4. Re-import the sheet into Orange Data Mining to refresh your decision tree.

The Dashboard tab contains live KPI cards and charts built from this sheet - see
columns L:U on this sheet for hidden chart-helper formulas (do not delete).
