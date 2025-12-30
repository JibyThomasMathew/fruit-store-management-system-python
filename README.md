# Fruit Store Management System

A **Python-based, command-line Fruit Store Management System** that simulates basic retail operations for a fruit shop. The application reads inventory data from a CSV file and allows users to interactively view fruit details, check stock availability, and calculate selling prices dynamically based on quality and demand.

This project is ideal for practicing **Python, Pandas, CSV handling, and Object-Oriented Programming (OOP)** concepts.

---

## Features

- Load fruit inventory from a CSV dataset  
- Display available fruits with unique IDs  
- View fruit quality using a grading system (A / B / C)  
- Check stock availability and pricing  
- Dynamic selling price calculation based on:
  - Fruit condition
  - Stock availability  
- View fruit description and country of origin  
- Save updated data back to CSV on exit  
- Interactive menu-driven command-line interface  

---

## Technologies Used

- **Python 3**
- **Pandas**
- **CSV file handling**
- **Object-Oriented Programming (OOP)**

---

## Project Structure

```
├── fruit_store.py
├── fruit_store_dataset.csv
├── README.md
```

---

## Dataset Requirements

The CSV file (`fruit_store_dataset.csv`) must contain the following columns:

- `fruit_id`
- `fruit_name`
- `condition` (A, B, or C)
- `in_stock_availability` (High, Medium, Low)
- `buy_price`
- `sell_price`
- `description`
- `origin`

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/fruit-store-management-system.git
   ```

2. Navigate to the project directory:
   ```bash
   cd fruit-store-management-system
   ```

3. Install dependencies:
   ```bash
   pip install pandas
   ```

4. Run the program:
   ```bash
   python fruit_store.py
   ```

5. Follow the on-screen menu instructions.

---

## Price Calculation Logic

Selling prices are dynamically adjusted based on:
- **Fruit quality** (A = Good, B = Moderate, C = Poor)
- **Stock availability** (High / Medium / Low)

Lower stock and better quality result in higher selling prices.

---

## Future Improvements

- Add purchase and checkout functionality
- User authentication (admin/customer roles)
- GUI or web-based interface
- Database integration instead of CSV
- Error handling and input validation enhancements

---

## Learning Outcomes

- Working with structured datasets using Pandas
- Building menu-driven CLI applications
- Applying real-world business logic in Python
- Understanding data persistence using CSV files

---

