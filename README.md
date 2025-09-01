# 📰 News Summarizer Desktop App

## 1. Overview of News Summarizer Desktop App

News comes to us in huge amounts every day, and it can be hard to keep
track of the most important points. Reading long articles takes time,
and people often just want quick highlights.

The **News Summarizer Desktop App** helps solve this by reading news
from PDF files, picking out the key headlines, grouping them into
sections (like Politics, Business, Sports, etc.), and creating short
summaries. This way, you get the important news quickly without reading
the whole paper.

------------------------------------------------------------------------

## 2. Technology Used

This app is built using simple but powerful tools:

-   **AI Model:** Uses **OpenAI GPT-4o-mini** to understand text,
    classify news into sections, and create summaries.\
-   **PDF Reading:** Uses **PyPDF2** to extract text from newspaper PDF
    files.\
-   **Parallel Processing:** Splits long text into smaller chunks and
    processes them faster with Python's **ThreadPoolExecutor**.\
-   **Desktop Interface:** Built with **Tkinter**, Python's built-in GUI
    library, so no extra frontend coding is required.\
-   **Secure Setup:** API keys are stored safely using **dotenv**, and
    logs are recorded for better tracking.

------------------------------------------------------------------------

## 3. Benefits

Some clear advantages of this app are:

-   **No extra frontend needed** -- Tkinter comes with Python, so it's
    lightweight and easy to run.\
-   **Simple design** -- Browse, extract, filter, and summarize news
    with just a few clicks.\
-   **Time-saving** -- Quickly get the main points without reading full
    articles.\
-   **Beginner-friendly** -- Code is easy to follow and uses common
    Python libraries.\
-   **Cross-platform** -- Works on Windows, Mac, or Linux without extra
    setup.

------------------------------------------------------------------------

## 4. Next Steps

This is the first version of the app. In the future, it can be improved
in many ways:

-   Make it into a ready-to-install software for non-technical users.\
-   Add support for news websites and RSS feeds, not just PDFs.\
-   Create mobile and web versions for easier access.\
-   Allow users to choose favorite categories (e.g., Sports only).\
-   Add support for multiple languages.\
-   Show analytics like trending topics and frequently covered news.

------------------------------------------------------------------------

## ⚙️ How to Run

1.  **Clone or download the project** to your computer.\

2.  **Install required Python libraries:**

    ``` bash
    pip install openai python-dotenv PyPDF2
    ```

3.  **Create a `.env` file** in the same folder and add your OpenAI API
    key:

        OPENAI_API_KEY=your_api_key_here

4.  **Run the app:**

    ``` bash
    python main.py
    ```

5.  The desktop app will open. Upload a newspaper PDF, extract
    headlines, and generate summaries.

------------------------------------------------------------------------
