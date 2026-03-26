# Assignment — Part 3: File I/O, APIs & Exception Handling

## Project Title
**Product Explorer & Error-Resilient Logger**

---

##  Overview
This project demonstrates real-world Python development:

- File Handling (Read & Write)
- API Integration using `requests`
- Exception Handling
- Logging System with timestamps

The application fetches product data from a public API, processes it, and handles all possible errors gracefully.

---

## Technologies Used
- Python 3
- Google Colab
- Requests Library
- DummyJSON API

---

##  API Used
DummyJSON Products API:  
https://dummyjson.com/products

---

##  Project Structure 


---

Features Implemented

###  Task 1: File I/O
- Created `python_notes.txt`
- Wrote and appended content
- Read file with line numbering
- Keyword-based search (case-insensitive)

---

###  Task 2: API Integration
- Fetch products (limit 20)
- Display formatted table
- Filter products (rating ≥ 4.5)
- Sort by price (descending)
- Fetch laptops category
- POST request to simulate product creation

---

###  Task 3: Exception Handling
- Safe division function (`safe_divide`)
- Safe file reader (`read_file_safe`)
- API error handling:
  - ConnectionError
  - Timeout
  - General exceptions
- Input validation loop for product lookup

---

###  Task 4: Logging System
- Created `error_log.txt`
- Logs include:
  - Timestamp
  - Function name
  - Error type
  - Error message
- Handles:
  - Connection errors
  - HTTP errors (e.g., 404)

---

##  Error Handling Strategy
- All API calls wrapped in `try-except`
- Custom logger used for tracking issues
- Prevents crashes and ensures smooth execution

---

##  How to Run

1. Open Google Colab
2. Upload `part3_api_files.ipynb`
3. Run all cells step-by-step
4. Download generated files:
   - `python_notes.txt`
   - `error_log.txt`

---

##  Sample Output

- Product table displayed
- Filtered product list
- Laptop category products
- Safe function outputs
- Error logs printed

---


##  Notes
- DummyJSON API is a mock API (no real data stored)
- Error logs persist across runs
- Code includes comments for clarity
