# 📚 Books to Scrape - Web Scraping Project

This project demonstrates how to use Python to scrape data from the [Books to Scrape](http://books.toscrape.com) website — a mock site created for practicing web scraping.

---

## 🔍 Objective

To extract information about all **1,000 books** listed on the site including:
- Title
- Price
- Star Rating
- Product Page Link

---

## 🛠 Tools Used

- `requests` – for sending HTTP requests  
- `BeautifulSoup` – for parsing HTML  
- `pandas` – for organizing and exporting data  
- `time` – to avoid overloading the server  
- `csv` – to save clean output

---

## 🔁 Key Features

✅ Pagination handling across all 50 pages  
✅ Star rating text converted to numerical values  
✅ DataFrame created and exported to `cleaned_books.csv`  
✅ Polite scraping using time delays

---

## 📊 Sample Output

| Title                             | Price | Rating |  
|----------------------------------|-------|--------|  
| A Light in the Attic             | £51.77| 3      |  
| Tipping the Velvet               | £53.74| 1      |  
| Soumission                       | £50.10| 1      |  

➡️ [View Full CSV](./cleaned_books.csv)

---

## 🙋‍♂️ Author

**Revanth Reddy Kurra**  
📊 Aspiring Data Analyst based in Munich  
🔗 [GitHub](https://github.com/kurrarevanthreddy14) | [LinkedIn](https://www.linkedin.com/in/revanth-reddy-kurra-6b632a2b6/)

---

Thanks for visiting! ⭐
