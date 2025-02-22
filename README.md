## Project Name: Brochure Generator

### Description
This Project is designed to generate and customize brochures by leveraging API-powered content generation, web scraping, and automated formatting techniques. It utilizes OpenAI for text generation, BeautifulSoup for web data extraction, and environmental configurations for secure API access.

### Installation
To set up the environment, follow these steps:
1. Install the necessary dependencies:
   ```sh
   pip install IPython beautifulsoup4 python-dotenv openai requests
   ```
2. Create a `.env` file in the root directory and add the required OpenAI API key:
   ```sh
   OPENAI_API_KEY=your_api_key_here
   ```
3. Launch Jupyter Notebook:
   ```sh
   jupyter notebook Brochure.ipynb
   ```

### Usage
1. Open `Brochure.ipynb` in Jupyter Notebook.
2. Execute the cells sequentially to generate brochure content.
3. Modify API parameters or input text as needed.
4. Save the generated brochure in the desired format.

### Dependencies
This project relies on the following Python libraries:
- `IPython.display` (for rendering output)
- `bs4` (BeautifulSoup for web scraping)
- `dotenv` (for handling environment variables)
- `json` (for data manipulation)
- `openai` (for AI-based content generation)
- `os` (for file handling)
- `requests` (for API calls)
- `typing` (for type hinting)

### Features
- AI-generated content using OpenAI API.
- Web scraping capabilities with BeautifulSoup.
- Secure environment configurations via `.env`.
- Automated brochure text formatting and customization.