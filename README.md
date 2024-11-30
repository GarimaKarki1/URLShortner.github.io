# URL Shortener

This Python program uses the **Cutt.ly API** to shorten long URLs into compact, shareable links. It's simple to use and provides error messages in case of issues.

---

## Features
- Shorten URLs using the Cutt.ly API.
- Handles HTTP errors gracefully.
- Clear error messages if an invalid API key or URL is provided.

---

## Requirements
Ensure you have the following installed:
- Python 3.6+
- `requests` library

Install the required library using:
```bash
pip install requests
```

---

## Setup and Configuration
1. Get your API key from [Cutt.ly](https://cutt.ly/).
2. Replace the placeholder in the code with your actual API key:
   ```python
   API_KEY = "your_actual_cuttly_api_key"
   ```

---

## Usage
1. Clone this repository or download the script.
2. Run the script in your terminal:
   ```bash
   python url_shortener.py
   ```
3. Enter the URL you wish to shorten when prompted.

### Example
```plaintext
=== URL Shortener ===
Enter the URL to shorten: https://example.com/very-long-url
Shortened URL: https://cutt.ly/abcd123
```

---

## Code Explanation

### Function: `shorten_url`
This function communicates with the Cutt.ly API to shorten a given URL.
- **Inputs**:
  - `api_key`: Your Cutt.ly API key.
  - `url_to_shorten`: The URL to be shortened.
- **Output**: A shortened URL or an error message.

### Main Script Flow
1. Prompts the user for a URL.
2. Checks if the API key is correctly set.
3. Calls `shorten_url` to process the URL.
4. Displays the result to the user.

---

## Screenshot
Below is a mock terminal screenshot for the program:
![image](https://github.com/user-attachments/assets/775baea6-70ec-4794-b312-a4219912d48f)
