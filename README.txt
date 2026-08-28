MACRO TRACKER V2.6

WHAT'S NEW
- Saved foods can now be edited.
- Removed the Custom Serving Name field entirely.
- Build a Meal is now a batch recipe builder:
  * name the meal
  * set total servings for the whole batch
  * add ingredients from saved foods
  * adjust each ingredient amount
  * choose ingredient unit/default serving
  * remove ingredients
  * see live whole-batch macros
  * see live per-serving macros
  * save the recipe with ingredient amounts and serving count
  * view the saved recipe later
  * edit the saved recipe later
  * log one or more servings in the diary
- Removed Water Goal logging-step setting.
- Keeps the six Daily Progress rings and water logging in Add to Diary.
- Includes migration logic for older saved data.

SAFETY BEFORE UPDATING
Use Export Backup in your current live app first. Updating the GitHub files should preserve browser localStorage, but a backup gives you a recovery copy.


V2.7 — BACKUP RESTORE
- Added an Import backup button beside Export backup.
- Compatible with older Macro Tracker backup JSON files.
- Restores foods, meals, diary history, water history, targets, water goal,
  custom units and kcal/kJ display preference.
- Deprecated custom serving-name and water logging-step fields are safely ignored.

RESTORE STEPS
1. Upload this version to the same GitHub repository.
2. Open the updated app.
3. Go to Targets/Settings.
4. Tap Import backup.
5. Select your macro-tracker-backup .json file.
6. Check the summary and confirm.
