# python-log-processing_Chahat_ECE-B_202501100700060



#  Log File Analyzer (Case Study 4)

##  Overview

This project processes a log file (`CS4.txt`) using Python and performs various file handling operations such as reading, classification, filtering, searching, and file pointer manipulation.

---

## Features

###  Task 1: File Reading

* Read file using:

  * `read()`
  * `readline()`
  * `readlines()`
* Outputs:

  * Total number of lines
  * First 2 lines
  * Last 2 lines

---

###  Task 2: Log Classification

Counts occurrences of:

* INFO
* WARNING
* ERROR

Stored in a Python dictionary.

---

###  Task 3: Filtered Files

Generates:

* `info_logs.txt`
* `warning_logs.txt`
* `error_logs.txt`

---

###  Task 4: Search Feature

* User inputs a keyword (e.g., ERROR)
* Matching lines are displayed
* Results saved in `search_result.txt`

---

###  File Pointer Operations

* Reads first 50 characters
* Uses `seek()` to navigate:

  * Beginning
  * Middle
  * Last 100 characters

---

##  Technologies Used

* Python (File Handling)

---

##  How to Run

```bash
python cs4_solution.py
```

---

##  Files Included

* `CS4.txt` → Input log file
* `cs4_solution.py` → Main Python script
* Output files:

  * `info_logs.txt`
  * `warning_logs.txt`
  * `error_logs.txt`
  * `search_result.txt`

---

##  Output Screenshot

<img width="376" height="248" alt="image" src="https://github.com/user-attachments/assets/d2c9a29c-ac0a-415c-bddf-44d119a03c63" />
<img width="407" height="294" alt="image" src="https://github.com/user-attachments/assets/0fbb1012-97d2-45d5-ac5e-df009cff154c" />
<img width="394" height="134" alt="image" src="https://github.com/user-attachments/assets/c5d87dc5-ab1f-49b2-ae45-5f0316e308ba" />
