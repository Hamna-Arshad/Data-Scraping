# Extraction of Sindh High Court District Courts using Selenium

This assignment automates the extraction of case information from the Sindh High Court District Courts website using **Python** and **Selenium**.  
The scraper navigates through case listings, opens detailed modals, and collects structured data from multiple subsections such as case history, connected cases, advocates, and parties.

---

## Features
- Navigate through paginated case listings.
- Extract key case metadata:
  - Serial number
  - Case category
  - Case number & year
  - Bench & circuit code
  - Case title & matter summary
  - Hearing dates, disposal date, and status
- Open case details modal and scrape subsections:
  - **Case History**
  - **Connected Cases**
  - **Misc Appln (CMA)**
  - **Case Advocates**
  - **Parties Details**
- Avoid stale element errors by re-fetching elements dynamically.
- Export structured results into JSON for further analysis.

---

## Tech Stack
- **Language**: Python 3.10+
- **Automation**: Selenium WebDriver
- **Browser**: Chrome/Chromium (with ChromeDriver)
- **Dependencies**:
  - `selenium`
---

