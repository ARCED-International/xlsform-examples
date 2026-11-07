# XLSForm examples

Tested, ready-to-upload XLSForm examples for ODK, KoboToolbox and SurveyCTO, one folder per pattern.
Every form compiles with [pyxform](https://github.com/XLSForm/pyxform) and ODK Validate, the same
check ODK Central runs when you upload a form.

Each example comes from a step-by-step guide on [SurveyLoopr](https://www.surveyloopr.com/docs/tips),
which explains the pattern, the common mistakes and the error messages they produce.

## Examples

| Pattern | Form | Guide |
|---------|------|-------|
| If statements: `if()`, AND/OR, nested if, select_multiple, scores, conditional constraints | [xlsform-if-statement.xlsx](xlsform-if-statement/xlsform-if-statement.xlsx) | [XLSForm if statement](https://www.surveyloopr.com/docs/tips/xlsform-if-statement) |

New examples are added as the guides are published.

## How to use a form

1. Download the `.xlsx` from its folder.
2. Upload it to ODK Central (Project > New form), KoboToolbox (Deploy > Upload XLSForm) or open it
   in Excel / Google Sheets to copy the rows you need into your own form.
3. Each example sits in its own group, so you can delete the groups you don't need.

## Checking the data these forms collect

A constraint or relevance rule stops many errors at the point of entry; the rest show up once interviews arrive.
[DataFlow](https://letdataflow.com) reads the same XLSForm conditions and checks every submission as it syncs. Its guides
explain [logic and consistency checks](https://letdataflow.com/checks/logic-checks), [range checks](https://letdataflow.com/checks/range-checks)
and the other [high-frequency checks](https://letdataflow.com/checks) a survey needs.

## License

The forms and text in this repository are licensed under
[Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE). Use them in your own surveys,
training material and courses; please credit "SurveyLoopr / ARCED International" with a link to the
guide or to this repository.

Maintained by [ARCED International](https://www.arced-international.com) and [SurveyLoopr](https://www.surveyloopr.com).
Found a mistake or want a pattern covered? Open an issue.
