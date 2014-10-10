| PATH                           | VERB | DESC                                          |
|--------------------------------|------|-----------------------------------------------|
| /                              | GET  | Info about program.                           |
| /login                         | GET  | Login page                                    |
| /login                         | POST | Process login.                                |
| /user/:userid                  | GET  | User page with pageable list of transactions. |
| /user/:userid/intake           | GET  | Form for user to enter daily take.            |
| /user/:userid/intake           | POST | Process submitted daily take.                 |
| /user/:userid/taxes            | GET  | Form to pay outstanding taxes.                |
| /user/:userid/taxes            | POST | Process tax payment.                          |
| /admin                         | GET  | Admin login page.                             |
| /admin                         | POST | Process admin login.                          |
| /admin/reports                 | GET  | Provide list of available reports             |
| /admin/reports/table/:from/:to | GET  | Table of data for date range                  |
| /admin/reports/chart/:from/:to | GET  | Chart of data for date range                  |