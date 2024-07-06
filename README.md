## YouTube Trending Videos Analysis

### Project Overview
This project involves analyzing YouTube trending videos to gain insights into what makes a video trend. By utilizing data analytics and visualization techniques, we uncover patterns and trends in video popularity, categories, duration, and other key attributes.

### Key Features
- **Data Collection:** Fetch trending videos data using the YouTube Data API.
- **Data Analysis:** Analyze video attributes such as views, likes, dislikes, comments, and categories.
- **Visualization:** Generate visualizations to represent the data insights using libraries like Matplotlib and Seaborn.
- **Export Results:** Export analysis results to CSV or other formats for further use.

### Tools & Technologies
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Requests
- **Development Tools:** Jupyter Notebook

### Installation
To get started with the project, follow these steps:
1. **Clone the repository:**
    ```sh
    git clone https://github.com/Matinnorouzi2023/Youtube-trending-analysis.git
    cd youtube-trending-analysis
    ```
2. **Create a virtual environment (optional but recommended):**
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```
3. **Install the required dependencies:**
    ```sh
    pip install -r requirements.txt
    ```
4. **Set up your YouTube Data API key:**
    - Obtain an API key from the [Google Developers Console](https://console.developers.google.com/).
    - Create a `.env` file in the project root directory and add your API key:
        ```
        YOUTUBE_API_KEY=your_api_key_here
        ```

### Usage
To use the analysis script, follow these steps:
1. **Fetch the trending videos data:**
    ```sh
    python scripts/fetch_trending_videos.py
    ```
2. **Run the analysis:**
    ```sh
    python scripts/analyze_trending_videos.py
    ```
3. **Generate visualizations:**
    ```sh
    python scripts/generate_visualizations.py
    ```

### Project Structure


- **data/**: Directory for storing raw and processed data.
- **notebooks/**: Jupyter notebooks for exploratory data analysis.
- **scripts/**: Python scripts for fetching data, analyzing, and generating visualizations.
- **.env**: File for storing environment variables (e.g., API keys).
- **requirements.txt**: List of dependencies required for the project.
- **README.md**: This README file.

### Configuration
Ensure you have the YouTube Data API key set up in the `.env` file. The configuration settings for the project can be adjusted in the script files as needed.

### Data Sources
The primary data source for this project is the YouTube Data API, which provides access to various video attributes, metadata, and statistics.

### Analysis
The analysis script (`analyze_trending_videos.py`) performs the following steps:
1. Load the fetched trending videos data.
2. Clean and preprocess the data.
3. Perform descriptive and inferential statistical analysis.
4. Identify patterns and trends in video attributes.
5. Generate visualizations to represent the findings.

### Contributing
We welcome contributions to improve this project. If you have suggestions, bug fixes, or new features to add, please submit a pull request or open an issue on the GitHub repository.

### License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

Thank you for using the YouTube Trending Videos Analysis project! If you have any questions or need further assistance, please feel free to reach out.

