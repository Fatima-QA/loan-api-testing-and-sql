# Loan API Testing and SQL Coursework

## Purpose

QA coursework documenting loan API test cases and links to database exercises.

## Artifacts

| File | Content |
|---|---|
| [C Fatimə QA task loans.xlsx](C%20Fatim%C9%99%20QA%20task%20loans.xlsx) | Loan API cases with preconditions, request steps, test data, expected responses, recorded actual results, and execution statuses |
| [C. Fatimə DB 1.docx](C.%20Fatim%C9%99%20DB%201.docx) | Links to 12 database exercises on DB Fiddle |

## Tools and formats

- REST API testing concepts and HTTP response validation
- Excel test documentation
- DB Fiddle for database coursework
- GitHub for versioned storage

## API coverage

The workbook includes positive and negative loan scenarios covering amount limits, permitted loan terms and purposes, missing fields, account ownership, unknown accounts, and repeated applications. The cases reference Bearer-token authentication, acceptance criteria, and endpoints such as POST /loans.

## Learning outcomes

- Translate API rules into concrete requests and expected responses.
- Check status codes and business-response fields together.
- Design invalid-input, authorization, and boundary scenarios.
- Record actual results separately from expected behavior.
- Organize database exercise references for review.

## Review the work

Download the workbook to inspect cases. Open the DOCX for the DB Fiddle exercise links. Recorded statuses reflect the coursework file; the API was not rerun for this repository documentation update. The linked SQL solutions have not been independently verified in this review.

## Next improvements

- Align the API workbook's headers and cells: the first case includes an extra acceptance-criteria label that shifts its fields.
- Standardize execution statuses and record environment, base URL, and execution date.
- Add the Postman collection and an environment template without credentials.
- Export SQL exercises as .sql files with schema, sample data, and expected results.

## Related work

[Manual testing](https://github.com/Fatima-QA/QA_ders_1_4) · [Java fundamentals](https://github.com/Fatima-QA/FatimaJamalova_Java)
