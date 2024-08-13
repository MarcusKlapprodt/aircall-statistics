# Aircall Statistics

This repository contains a Jupyter Notebook that extends and enriches the statistics available for the Aircall app. By leveraging Python, this notebook provides insightful KPIs and metrics, allowing for a deeper understanding of call patterns and performance. The notebook outputs the results directly within itself and also generates an Excel file that summarizes all data in separate sheets for easy access and analysis.

## Features

The notebook answers the following key questions:

- **Hotline Call Volume**: How many calls does each hotline receive?
- **Peak Hours**: During which hour do we receive the most calls?
- **Call Distribution by Weekday**: How many calls are received per weekday?
- **Weekly Call Trends**: Calls per calendar week (KW).
- **Aggregate Weekday Call Data**: How many calls per weekday across all hotlines?
- **Support Hotline Insights**: 
  - Average duration of calls on the support hotline.
  - Missed calls statistics.
  - Missed calls per team-hotline.
  - Detailed list of missed calls on the support hotline.
  - Missed calls distribution by hour.

## Installation

To use this project, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/MarcusKlapprodt/aircall-statistics.git
    cd aircall-statistics
    ```

2. **Create a virtual environment**:
    ```bash
    python3 -m venv .env
    source .env/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Jupyter Notebook**:
    ```bash
    jupyter notebook
    ```

5. **Generate the Excel report**: The notebook will automatically generate an Excel file summarizing the statistics in separate sheets.

## Output

- **In-Notebook Results**: All statistics and analyses are displayed directly within the Jupyter Notebook.
- **Excel Report**: A comprehensive Excel file is created, containing all the KPIs and insights in separate sheets, making it easy to share and review the data.

## License

This project is licensed under the [GPL-3.0 License](LICENSE).

---

Feel free to contribute, report issues, or suggest features. Enjoy analyzing your Aircall data with deeper insights!
