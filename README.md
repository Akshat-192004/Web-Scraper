#  Web Scraper 

This project is a Python-based web scraper built to extract and organize legal documents from the Legal Information Institute (LII) of India. It efficiently fetches content, converts it to `.docx` or `.pdf`, and logs detailed progress and statistics to support transparency and reusability.

---

## Features

-  Scrapes legal document links from target URLs
-  Optimized and multithreaded for performance
-  Converts fetched content into `.docx` and `.pdf` formats
-  Tracks detailed statistics and scraping status
-  Maintains logs of fetched, pending, and processed URLs

---

## 📁 Project Structure

| File/Notebook               | Description                                                                 |
|----------------------------|-----------------------------------------------------------------------------|
| `optimized.ipynb`          | Main scraper notebook containing the core logic                             |
| `count.ipynb`              | Counts the total number of URLs across all input files                      |
| `stats.ipynb`              | Generates summary statistics: total records, unique entries, time, formats |
| `urls_done.txt`            | URLs that have been successfully fetched and saved                          |
| `urls_left.txt`            | Remaining URLs pending processing                                           |
| `final.log`                | List of all successfully fetched files                                      |
| `new_logs.log`             | Timestamped log of each fetched file                                       |
| `stage4.rar`               | Archive of results or intermediate outputs                                  |

---

## Sample Statistics Tracked

- ✅ Total URLs processed
- ❌ Total URLs left
- 📄 Number of `.docx` files
- 📑 Number of `.pdf` files
- 🕓 Time taken
- 🧾 Total logs generated



##  Notes

- This scraper is tailored and may need adjustments for other sources.
- Make sure the environment has internet access and required libraries installed.


