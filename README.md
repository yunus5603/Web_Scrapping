# Web Scrapping using Flask

This is a web scraping application built using Flask to scrape product reviews from Flipkart and store them in a MongoDB database.

## Table of Contents

- [Introduction](#introduction)
- [Setup](#setup)
- [Usage](#usage)
- [Technologies](#technologies)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This Flask-based web scraping application extracts product reviews from Flipkart's website. It utilizes BeautifulSoup and Flask-CORS to scrape and display reviews. The extracted reviews are then stored in a MongoDB database. The application includes two main routes: `/` for the homepage and `/review` for the review extraction and storage process.

## Setup

1. Clone this repository to your local machine:

```sh
   git clone https://github.com/your-username/flipkart-review-scraper.git
   ```
2. Navigate to the project directory:
```sh
   cd flipkart-review-scraper
   ```
3. Install the required Python packages using pip:
```sh
   pip install flask flask-cors requests beautifulsoup4 pymongo
  ```
Replace the MongoDB connection URL in the code with your own MongoDB connection URL.

## Usage

1. Run the Flask application:
```sh
python app.py
```
2. Access the application by opening a web browser and navigating to http://localhost:5000.
3. Enter the product you want to search for and click the "Search" button.
4. The application will scrape the reviews for the entered product from Flipkart and store them in the MongoDB database.
5. The scraped reviews will be displayed on the results page.

## Technologies
- Flask: Micro web framework for building web applications.
- Flask-CORS: Extension to handle Cross-Origin Resource Sharing (CORS) in Flask applications.
- BeautifulSoup: Python library for pulling data out of HTML and XML files.
- MongoDB: NoSQL database used for storing scraped reviews.

## Contributing
Contributions are welcome! If you find a bug or want to enhance the application, feel free to open an issue or submit a pull request.
1. Fork the repository.
2. Create a new branch for your feature or bug fix:
```sh
git checkout -b feature/your-feature-name
```
3. Make your changes and commit them:
```sh
git commit -m "Add your commit message here"
```
4. Push to the branch:
```sh
git push origin feature/your-feature-name
```
5. Create a pull request explaining your changes.

## License
This project is licensed under the MIT License.
```sh

Please make sure to replace `your-username` in the repository URL and add a `LICENSE` file with the appropriate license text if you haven't already. Also, feel free to adjust any of the content or sections to better match your project's specifics.
```
