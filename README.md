---

# 📧 Cold Email Generator

A **Cold Email Generator** powered by Streamlit and LangChain to help you craft personalized cold emails by extracting job details from URLs. This tool fetches job descriptions, analyzes required skills, and matches them with your portfolio links, generating a fully tailored cold email for job applications.

## Home
![image](https://github.com/user-attachments/assets/4caae9f1-ad2a-447e-bfba-8538ec5a16a3)

## Generated Mail
![image](https://github.com/user-attachments/assets/54754b20-fedb-4193-a26a-509657d49e89)


## 🚀 Features

- **Automated Job Data Extraction:** Scrape job descriptions from URLs using `WebBaseLoader`.
- **Personalized Cold Emails:** Automatically generate personalized emails based on job skills and match them with relevant projects in your portfolio.
- **Streamlit-based UI:** Simple and interactive web-based UI for inputting URLs and generating cold emails.
- **Portfolio Integration:** Leverage your existing portfolio to include relevant projects and links in your cold emails.
- **Markdown Email Output:** Emails are outputted in easy-to-copy markdown format.

## 🛠️ Technology Stack

- **Streamlit:** Interactive UI framework for creating web applications.
- **LangChain:** Language model integration for processing and extracting data from job descriptions.
- **Custom Portfolio & Chain Models:** 
  - `Chain`: Handles the logic for processing data and extracting job-related information.
  - `Portfolio`: Manages your project portfolio, querying relevant projects based on skills listed in job descriptions.
- **WebBaseLoader:** Scrapes job descriptions directly from URL input.
- **Python:** Core programming language used to build the backend of the application.

## 🔧 Installation and Setup

To run this project locally, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/cold-email-generator.git
cd cold-email-generator
```

### 2. Install Dependencies

Make sure you have Python 3.8+ installed. Then, install the necessary Python packages:

```bash
pip install -r requirements.txt
```

### 3. Run the Application

Launch the Streamlit application:

```bash
streamlit run app.py
```

The application will be accessible at `http://localhost:8501`.

## 📄 Usage

1. Enter the URL of the job listing you are interested in applying to.
2. Click the **Submit** button to extract the job description.
3. The tool will:
   - Scrape the job listing.
   - Analyze the job's required skills.
   - Match relevant skills to your portfolio.
   - Generate a cold email tailored to the job.
4. The output will appear in markdown format, which can be copied and sent via email.

## 📁 Project Structure

```bash
cold-email-generator/
│
├── chains.py              # Chain class for processing job data and LLM-based tasks
├── portfolio.py           # Portfolio class for managing and querying project links
├── app.py                 # Main Streamlit app file
├── utils.py               # Utility functions, including text cleaning
├── requirements.txt       # Required Python packages
└── README.md              # Project documentation
```

## 🌟 Key Modules

- **`chains.py`:** Manages LLM-based operations, including job data extraction and email writing.
- **`portfolio.py`:** Handles portfolio logic, linking job skills to relevant project experience.
- **`utils.py`:** Provides utility functions for cleaning job descriptions before processing.

## 📧 Contact

For questions or feedback, feel free to reach out and create an issue.

## 🔗 Useful Links

- [Streamlit Documentation](https://docs.streamlit.io/)
- [LangChain Documentation](https://python.langchain.com/)

---

**Cold Email Generator** simplifies your job application process by turning job descriptions into personalized cold emails with just one click! Let your portfolio speak for itself.

---
