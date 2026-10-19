# XLSForm if statement

`if(condition, value_if_true, value_if_false)` in the `calculation` column of a `calculate` row.
ODK, KoboToolbox and SurveyCTO all read it the same way.

**Form:** [xlsform-if-statement.xlsx](xlsform-if-statement.xlsx)
**Full guide:** https://www.surveyloopr.com/docs/tips/xlsform-if-statement

## What's in the form

| Group | Pattern |
|-------|---------|
| 1 | Basic syntax: `if(${age} >= 18, 'adult', 'child')` |
| 2 | Two conditions with `and` (not Excel's `AND()`) |
| 3 | Nested `if()`: Food Consumption Score bands (WFP cut-offs 21 / 35) |
| 4 | `selected()` with a select_multiple (never `= '4'`) |
| 5 | A WASH score that adds `if()` results, safe with skipped questions |
| 6 | Question text that changes with an earlier answer (`he` / `she`) |
| 7 | A constraint whose limit depends on another answer (weeks vs months) |

## Rules that catch most errors

- Lowercase `if`; `IF(` fails.
- Exactly three arguments; use `''` for "nothing".
- No leading `=`; XLSForm is not an Excel formula.
- `and` / `or` / `!=` / `div` / `concat()`, not `AND()` / `OR()` / `<>` / `/` / `&`.

Licensed under CC BY 4.0. Credit: SurveyLoopr / ARCED International.
