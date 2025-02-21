# SQL-Project: Query a Digital Music Store Database

## Project Overview
This project analyzes a digital music store's database to extract valuable insights using SQL queries. The database used is the **Chinook Database**, a sample database that simulates a digital music store. The analysis focuses on answering key business-related questions regarding sales, customers, and music trends.

## Dataset
The project utilizes the **Chinook Database (chinook.db)**, which contains tables such as:
- **Customers**: Information about customers
- **Invoices**: Purchase records of customers
- **InvoiceLines**: Details of each purchased track
- **Tracks**: Information about songs available in the store
- **Artists**: Details about music artists
- **Albums**: Information on albums and their respective artists
- **Genres**: Categorization of music tracks
- **Employees**: Store staff details
- **Playlists**: Predefined playlists with associated tracks

## Files in the Repository
- `chinook.db`: The SQLite database file used for analysis.
- `SQL Queries.txt`: A collection of SQL queries executed on the database to extract insights.
- `Question 1.csv`, `Question 2.csv`, `Question 3.csv`, `Question 4.csv`: CSV files containing the results of the executed SQL queries.
- `Questions and Visualization.pdf`: A document presenting the analysis results with visualizations and explanations.
- `README.md`: This file, providing an overview of the project.

## Analysis and Key Questions
The analysis addresses the following business questions:
1. **Who are the top customers based on total purchase value?**
2. **Which genre generates the highest revenue?**
3. **Which artist has the most sales in the store?**
4. **What are the monthly sales trends?**

## Tools Used
- **SQLite** for querying the database
- **Python (Pandas, Matplotlib, Seaborn)** for data analysis and visualization (if applicable)
- **Excel/Google Sheets** for tabular data representation

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Analyze-Digital-Music-Store-Database.git
   ```
2. Open `chinook.db` using an SQLite viewer or execute the queries in `SQL Queries.txt`.
3. Review the CSV files for extracted insights.
4. Refer to `Questions and Visualization.pdf` for analysis interpretations and visual representations.

## Conclusion
This project demonstrates how SQL can be used to analyze a digital music store's database effectively. The insights derived can help businesses optimize their sales strategies, understand customer preferences, and improve inventory management.

For any questions or suggestions, feel free to contribute or reach out!

## License
This project is for educational purposes and is open for contributions and modifications.

