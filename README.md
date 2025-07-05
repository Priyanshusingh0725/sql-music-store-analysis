# 🎵 SQL Portfolio Project: Music Store Analysis

Welcome to my **SQL Portfolio Project**, where I analyze a music store dataset using **PostgreSQL** and the **Chinook Sample Database**. This project demonstrates my ability to write and organize SQL queries — from simple `SELECT` statements to advanced CTEs and window functions — to extract meaningful business insights.

---

## 📌 **Project Overview**

The goal of this project is to:

- Practice and showcase my SQL query writing skills.
- Extract valuable business insights from a normalized relational database.
- Demonstrate practical data analysis techniques using SQL.

All queries are grouped by difficulty level (*Easy, Moderate, Advanced*), showing a clear learning path and depth of understanding.

---

## 🗂️ **Schema Used**

The project uses the **Chinook Sample Database**, which models a digital music store with the following key tables:

- **`customer`** — Customer details.
- **`employee`** — Employees and managers.
- **`invoice`** — Invoice records for customer purchases.
- **`invoice_line`** — Detailed items within each invoice.
- **`track`** — Music tracks.
- **`album`** — Albums.
- **`artist`** — Artists.
- **`genre`** — Genres.
- **`playlist`** — Playlists.
- **`playlist_track`** — Tracks within playlists.

---

## ✅ **Query Categories**

The project covers multiple levels of SQL complexity:

### 🔹 **Easy Level**
Basic data retrieval, simple `SELECT` statements, filtering, grouping, and ordering.

**Examples:**
- List all customers and employees.
- Show all tracks with unit prices.
- Count total customers.
- List albums with artist names.
- Find top 5 most expensive tracks.

---

### 🔸 **Moderate Level**
Intermediate queries using `JOIN`, `GROUP BY`, `ORDER BY`, subqueries, and basic window functions.

**Examples:**
- Find the customer who spent the most.
- Identify the employee with the most supported customers.
- Find the track that generated the highest revenue.
- Top 5 most purchased genres.
- Average invoice totals per country.
- Top 3 customers in each country by spending.

---

### 🔺 **Advanced Level**
Advanced techniques like **CTEs**, nested subqueries, advanced `JOIN`s, and ranking.

**Examples:**
- Albums with more tracks than the average.
- Tracks never purchased.
- Genres with the highest average track price.
- Customers spending above the overall average.
- Top artist by total number of tracks.

---

## 📝 **Business Insights Summary**

Here are some key insights derived from this project:

- ✅ **All tracks have been purchased at least once**, indicating healthy inventory turnover.
- ✅ **Customers from the USA and Canada spend the most**, highlighting strong markets.
- ✅ **Rock is the top-selling genre**, showing audience preference.
- ✅ **The top artist has over 200 tracks**, contributing significantly to the catalog.
- ✅ **All employees are engaged with customers**, showing strong support operations.
- ✅ **No artist remains unpurchased**, reflecting diverse sales across the catalog.

---

## ⚙️ **How to Use**

To run the queries yourself:

1. **Install PostgreSQL**  
   If you don’t have it installed, get it from the [official PostgreSQL website](https://www.postgresql.org/download/).

2. **Load the Chinook Database**  
   Download the PostgreSQL version of the Chinook database from the [official Chinook repository](https://github.com/lerocha/chinook-database) and restore it to your local PostgreSQL server.

3. **Connect Using a SQL Client**  
   Use `pgAdmin`, `DBeaver`, `DataGrip`, or the `psql` CLI to connect to your database.

4. **Run the Queries**  
   Copy and paste queries from the `project.sql` file into your SQL editor to execute them and explore results.

---

## 🚀 **Why This Project Matters**

This portfolio piece shows not only my technical proficiency in SQL but also my ability to structure, comment, and document queries in a clean, maintainable way — a crucial skill for real-world data analysis and business intelligence roles.

---

## 📁 **Project Structure**

```

├── project.sql         # Full SQL script with all queries, grouped by difficulty
├── README.md           # This project overview and instructions

```

---

## 💡 **Next Steps**

- Expand the **Expert/Beyond-Hard** section with more advanced analytics.
- Visualize key results in a BI tool or dashboard.
- Apply similar analyses to larger, real-world datasets.

---

**Thank you for checking out this project!**  
If you find it useful or have feedback, feel free to connect and share ideas! 🎉
```

---


