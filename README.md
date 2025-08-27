# Your Text, Your Style – Auto-PPT Generator

[cite_start]This web application transforms bulk text, markdown, or prose into a fully formatted PowerPoint presentation that matches the look and feel of your chosen template[cite: 1, 2].

**Live Demo Link:** [(https://autopptgenerator-raghaviyengar.streamlit.app/)



---

## Features

* [cite_start]**Intelligent Content Structuring**: Paste a large block of text and the app intelligently maps it to a reasonable number of slides[cite: 5, 21, 23].
* [cite_start]**Custom Templates**: Upload your own `.pptx` or `.potx` file to have the generated presentation match your style, including colors, fonts, and layouts[cite: 8, 22].
* **Multi-LLM Support**: Supports multiple Large Language Model providers. [cite_start]Simply choose your provider and enter your API key[cite: 7, 24].
* [cite_start]**Secure**: Your API key is used only for the current session and is never stored or logged[cite: 17, 48].

---

## Setup Instructions

Follow these steps to run the application locally.

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/YourUsername/YourRepoName.git](https://github.com/YourUsername/YourRepoName.git)
    cd YourRepoName
    ```

2.  **Create a Virtual Environment**
    It's recommended to use a virtual environment to manage dependencies.
    ```bash
    # For macOS/Linux
    python3 -m venv venv
    source venv/bin/activate

    # For Windows
    python -m venv venv
    .\venv\Scripts\activate
    ```

3.  **Install Dependencies**
    This project's dependencies are listed in the `requirements.txt` file.
    ```bash
    pip install -r requirements.txt
    ```

---

## Usage Instructions

Once the setup is complete, you can run the application.

1.  **Run the Streamlit App**
    In your terminal, run the following command:
    ```bash
    streamlit run app.py
    ```
    Your web browser will automatically open with the application running.

2.  **Use the Application**
    * **Step 1: Paste Content**: Paste the text you want to convert into the "Paste Your Content" text area.
    * [cite_start]**Step 2: Provide Guidance (Optional)**: Give the AI a one-line instruction for the tone or structure (e.g., "make this an investor pitch deck")[cite: 6].
    * **Step 3: Upload Template**: Upload a `.pptx` or `.potx` file that has the style you want.
    * **Step 4: Configure LLM**: Choose your LLM provider (OpenAI, Anthropic, or Google Gemini) and paste your API key into the password field.
    * **Step 5: Generate**: Click the "Generate Presentation" button.
    * [cite_start]**Step 6: Download**: Once processing is complete, a download button will appear for you to save your new `.pptx` file[cite: 19].

---

## Project Summary

*(This is where you would paste the "Short Write-up" content we drafted earlier, explaining how text is parsed and how styling is applied.)*
