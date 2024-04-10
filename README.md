# Image Scraper Project

This is a Python Flask project for scraping images from a predefined query set at compile time. The scraped images are stored both locally and in a MongoDB database.

## Features

- Scrapes images based on predefined queries.
- Stores scraped images in a local folder.
- Saves scraped images metadata in a MongoDB database.

## Prerequisites

- Python 3.x
- Flask
- pymongo
- MongoDB
- Internet connection (for scraping images)

## Installation

1. Clone the repository: `git clone https://github.com/yourusername/image-scraper.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Set up MongoDB:

- Install MongoDB on your system.
- Start MongoDB service.

## Usage

1. Run the Flask application: `python app.py`
2. Open your web browser and go to `http://localhost:5000` to view the application.

3. The images will be scraped based on predefined queries set in the code and stored in the local folder specified in the configuration.

## Configuration

- The queries to be used for scraping images are defined in the `queries.py` file.
- MongoDB connection details are set in the `config.py` file.
  
## Contributions

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## Acknowledgements

- Flask
- pymongo
- MongoDB
