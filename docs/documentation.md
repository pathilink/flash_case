# Documentation

## cards 

| Column | Description | Type | Changes | 
|-|-|-|-|
| card_number | Id of the card. | nominal | int -> string |
| card_model | Card model (PIN or contactless). | nominal ||
| company_id | Id of the company where the person works. | nominal ||
| employee_id | Employee id. | nominal ||
| valid_thru | Card expiry date. | date | str -> date|
| period | Quarter in the year. | ordinal | New variable. |


## cards_status

| Column | Description | Type | Changes | 
|-|-|-|-|
| card_number | Id of the card. | nominal | int -> string |
| card_model| Card model (PIN or contactless). | nominal ||
| card_type | Card material (Plastic). | nominal | Drop column. |
| card_status | Card situation (Open; Permanently terminated; Temporarily blocked). | nominal ||
| started_at | Card status start. | date | str -> date|
| ended_at | Card status end. | date | str -> date|
| period_started_at | Start of card status by quarter. | ordinal | New variable. |
| period_ended_at | End of card status by quarter. | ordinal | New variable. |


## cards_transactions

| Column | Description | Type | Changes | 
|-|-|-|-|
| card_number | Id of the card. | nominal | float -> string |
| transaction_id | Id of transaction. | nominal ||
| transaction_date | Date of transaction. | date | str -> date|
| amount | Amount spent. | continuous ||
| period | Quarter in the year. | ordinal | New variable. |
