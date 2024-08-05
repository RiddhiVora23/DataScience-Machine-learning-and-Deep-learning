# Car Dealership Web Scraping


## Abstract

This project collects information about certified pre-owned Mercedes-Benz cars available within a 20-mile radius. It utilizes Beautiful Soup for web scraping, requests for HTTP requests, and pandas for data manipulation and analysis. The gathered data includes car names, mileage, dealer names, ratings, review counts, and prices, which are organized into a pandas DataFrame named 'car dealer.' This notebook serves as a practical guide for web scraping and data extraction from car dealership websites.

## Why Choose This Project?

- **Data Acquisition**: Gather valuable data from websites for analysis and research.
- **Data Analysis**: Perform data analysis to gain insights and make informed decisions.
- **Automation**: Save time by automating data collection.
- **Research and Study**: Collect and analyze data for academic or professional research.
- **Market Research**: Conduct market research, competitive analysis, and pricing comparisons.
- **Skill Development**: Enhance skills in data extraction, manipulation, and programming.

## Methodology

1. **Imports**: Import necessary libraries (Beautiful Soup, requests, pandas).
2. **HTTP Request**: Fetch website content using an HTTP GET request.
3. **Status Code**: Check HTTP response status code.
4. **Soup Object**: Parse HTML content using Beautiful Soup.
5. **Target Data**: Identify target elements (car name, mileage, dealer name, rating, review count, price).
6. **Data Extraction**: Extract data using Beautiful Soup.
7. **For-Loop**: Store data in lists and iterate through results.
8. **Create DataFrame**: Organize data into a pandas DataFrame.
9. **Data Cleaning**: Clean 'Review Count' column.
10. **Final Output**: Cleaned 'car dealer' DataFrame.

## Tools Used

- **Beautiful Soup**: For parsing HTML and extracting data.
- **Requests**: For making HTTP requests.
- **Pandas**: For data manipulation and analysis.

## Data Characteristics

- **Data Source**: ['https://www.cars.com/shopping/results/](https://www.cars.com/shopping/results/)
- **Data Structure**: Tabular form in a pandas DataFrame.
- **Data Columns**:
  - **Name**: Vehicle names.
  - **Mileage**: Vehicle mileage.
  - **Dealer Name**: Dealer names.
  - **Rating**: Vehicle ratings.
  - **Review Count**: Number of reviews.
  - **Price**: Vehicle prices.
- **Data Cleaning**: Removing parentheses and whitespace from 'Review Count' column.

## Challenges Faced

- **Website Structure Changes**: Periodic updates may be required due to changes in website structure.
- **Data Cleaning Complexity**: More complex cleaning may be necessary for real-world datasets.

## Conclusion

This project demonstrates the use of Python libraries for web scraping, data extraction, and organization. It provides valuable insights into certified pre-owned Mercedes-Benz cars and highlights the practical application of web scraping techniques.

## References

- [Web Scraping Using Beautiful Soup and Selenium](https://medium.com/ymedialabs-innovation/web-scraping-using-beautiful-soup-and-selenium-for-dynamic-page-2f8ad15efe25)
- [Using Python for Web Scraping](https://medium.com/@ramjoshi.blogs/using-python-for-web-scraping-using-beautiful-soup-scrapy-and-selenium-c9819c023ea7)

