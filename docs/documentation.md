# Documentation

## cards 

| Column | Description | Type | Changes | Questions |
|-|-|-|-|-|
| card_number | Id of the card. | nominal | int -> string ||
| card_model | Card model (PIN or contactless). | nominal |||
| company_id | Id of the company where the person works. | nominal |||
| employee_id | Employee id. | nominal |||
| valid_thru | Card expiry date. | date | str -> date||


## cards_status

| Column | Description | Type | Changes | Questions |
|-|-|-|-|-|
| card_number | Id of the card. | nominal | int -> string ||
| card_model| Card model (PIN or contactless). | nominal |||
| card_type | Card material (Plastic). | nominal | Drop column. ||
| card_status | Card situation (Open; Permanently terminated; Temporarily blocked). | nominal |||
| started_at | Card start. | date | str -> date||
| ended_at | Card end. | date | str -> date||


## cards_transactions

| Column | Description | Type | Changes | Questions |
|-|-|-|-|-|
| card_number | Id of the card. | nominal | float -> string ||
| transaction_id | Id of transaction. | nominal |||
| transaction_date | Date of transaction. | date | str -> date||
| amount | Amount spent. | continuous |||

