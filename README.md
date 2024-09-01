# 🌐 Web Scraping with Gemini 🛠️

Welcome to the **Web Scraping with Gemini** project! 🚀 This project demonstrates how to leverage the power of web scraping along with Google's Gemini model to extract and process web data efficiently.

## 📁 Project Structure

- **main.py**: The entry point of the project. It orchestrates the entire web scraping and Gemini interaction.
- **parse.py**: Contains the logic to parse and clean the data extracted from websites.
- **scrapping.py**: The core script responsible for scraping websites using Selenium and BeautifulSoup.
- **requirements.txt**: Lists all the dependencies required to run this project.

## 📦 Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Khatri4/web-scraping-with-gemini.git
   cd web-scraping-with-gemini
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## 🔑 API Key Setup

To use the Gemini model, you'll need to set up your own API key:

1. Obtain your API key from the Gemini model provider.
2. Create a `.env` file in the root directory of the project.
3. Add your API key to the `.env` file:
   ```
   GEMINI_API_KEY=your-api-key-here
   ```

## 🚀 How to Run

1. Make sure your environment is set up correctly (e.g., API keys, environment variables).
2. Run the `main.py` script using streamlit command:
   ```bash
   streamlit run main.py
   ```
## 🛠️ Features
- **Web Scraping**: Extract data from websites using Selenium and BeautifulSoup.
- **Data Parsing**: Clean and organize the extracted data for further processing.
- **Google Gemini Integration**: Use the power of Gemini to analyze and process the scraped data.

## 💡 Use Cases

- **Content Aggregation**: Automatically gather articles, blogs, or news from multiple websites for analysis or reporting.
- **Market Research**: Collect and analyze product information, reviews, and ratings from e-commerce sites.
- **Data Mining**: Extract large datasets from various websites for training machine learning models.
- **Competitor Analysis**: Monitor competitors' websites for changes in content, pricing, or product offerings.

## 🛠️ Technology Used

- **Python**: The main programming language used.
- **Selenium**: For automating web browsers to scrape dynamic content.
- **BeautifulSoup**: For parsing HTML and XML documents to extract data.
- **Google Gemini**: The LLM (Large Language Model) used to analyze and process the scraped data.
- **Streamlit**: To create an interactive web interface for displaying the results.
- **LangChain**: To streamline the interaction between the scraped data and the Gemini model.


## 📄 License

This project is licensed under the MIT License.
