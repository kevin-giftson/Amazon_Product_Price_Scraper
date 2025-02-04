# Amazon Product Price Scraper

## **Overview**
The Amazon Product Price Scraper is a Streamlit-based application that allows users to:
- Scrape product details (title and price) from multiple Amazon URLs.
- Email a compiled price report to the specified recipient.
- Save price history in a CSV file for future tracking.

---

## **Features**
- **Scrape Multiple URLs**: Input a list of Amazon product URLs, and the app retrieves their titles and prices.
- **Email Integration**: Send product details in a formatted email to any valid recipient.
- **CSV Storage**: Automatically logs product details with a timestamp in `price_history.csv`.
- **Streamlit Interface**: Intuitive user interface for easy use.

---

## **Installation**

1. Clone this repository:
   ```bash
   git clone https://github.com/kevin-giftson/Amazon_Product_Price_Scraper.git
   cd Amazon_Product_Price_Scraper
   ```
2. Install the required Python packages:
  ````bash
  pip install -r requirements.txt
  ```
---

## **How to Use**

- **1, Run the app:**
  ```bash
  streamlit run app.py
  ```
- **2.Input Details:**
  - Enter Amazon product URLs (one per line) in the text area.
  - Provide a valid recipient email address.

- **3.Scrape and Send:**
  - Click the "Scrape and Send Email" button to:
    - Retrieve product details.
    - Display results on the Streamlit app.
    - Email a detailed product price report.
    - Save data to price_history.csv.

## **Dependencies**
- Python 3.8 or above
- Required Libraries:
  - streamlit
  - requests
  - beautifulsoup4
  - smtplib
  - csv
  - email
  - datetime

## **File Structure**
   ```bash
amazon-product-price-scraper/
├── new_app.py             # Main application script
├── requirements.txt       # Required Python packages
├── price_history.csv      # CSV file for price history
└── README.md              # Documentation
   ```
