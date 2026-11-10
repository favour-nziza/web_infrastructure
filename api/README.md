# API project

Python 3 scripts that read employee TODO data from the JSONPlaceholder REST API
(`https://jsonplaceholder.typicode.com`) and export it to JSON.

## Files

- `2-export_to_JSON.py`: exports one employee's tasks to `USER_ID.json`.
  Usage: `./2-export_to_JSON.py 2`
- `3-dictionary_of_list_of_dictionaries.py`: exports every employee's tasks to
  `todo_all_employees.json`. Usage: `./3-dictionary_of_list_of_dictionaries.py`

## Requirements

Python 3 only, standard library only (`json`, `sys`, `urllib`).
