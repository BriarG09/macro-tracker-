MACRO TRACKER V2.2

NEW:
- Baby pink accent theme
- Custom food units (g, mL, L, oz, cup, tbsp, tsp, piece + your own custom units)
- Optional serving names
- Energy entry/display in kcal or kJ
- 6th daily progress ring for water
- Customisable water goal:
  * mL or L
  * custom container name such as Stanley bottle
  * quarter/half/whole logging increments
- Added meal categories:
  * Pre-workout
  * Post-workout
  * Dessert
- Existing:
  * searchable foods
  * multi-ingredient meal builder
  * previous/next day navigation
  * editable macro goals
  * weekly averages
  * PWA/offline support

IMPORTANT:
This version uses the same localStorage keys for existing foods/meals/diary where possible,
but the food data model has been expanded. Existing older foods may need to be re-saved
if their measurement fields are missing.


V2.2.1 FIX
- Fixed Daily Progress dashboard rendering bug.
- Calories, Protein, Carbs, Fat, Fibre, and Water now render as six independent circular progress rings.
- Water logging remains below the rings as a separate input control.


V2.3 DASHBOARD FIX
- Removed reliance on automatic browser globals created from HTML element IDs.
- Added explicit DOM bindings for Safari and preview compatibility.
- Added migration for older saved food records.
- Daily Progress now explicitly renders SIX rings:
  Calories, Protein, Carbs, Fat, Fibre, Water.
- Water logging remains below the six rings.
- App subtitle shows V2.3 so you can confirm you are viewing the new build.


V2.4 SIX-RING DASHBOARD
- Six progress rings are now hard-coded into the HTML and are always visible:
  Calories, Protein, Carbs, Fat, Fibre, Water.
- JavaScript only updates ring values/progress.
- This prevents an unrelated JS rendering issue from making the macro rings disappear.
- Header visibly says V2.4 SIX-RING DASHBOARD so the build is easy to identify.


V2.5
- Kept all six Daily Progress rings: Calories, Protein, Carbs, Fat, Fibre, Water.
- Moved the Log Water controls out of Daily Progress.
- Log Water now sits inside the Add to Diary section.
- Water logged there still updates the Water progress ring at the top.
