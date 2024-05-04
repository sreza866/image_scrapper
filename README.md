
To access your flask application open new tab in and paste the url:
```
https://{your_url}.app:5000/
```
=======
# Image Scraping Project

This project is a web application built with Flask for scraping images from Google search results and storing them in a MongoDB database. It allows users to enter a search query, retrieve images related to the query, and save them for later use.

## Features

- Web interface for entering search queries and viewing scraped images.
- Integration with Google Image Search for retrieving images.
- Storage of scraped images in a MongoDB database.
- Error logging using Python's logging module.

## Prerequisites

Before running the application, make sure you have the following installed:

- Python 3.x
- Flask
- Flask-CORS
- Requests
- BeautifulSoup
- pymongo
- MongoDB

## Installation

1. Clone the repository:

   
   ```git clone https://github.com/your_username/image-scraping-project.git```
2. Install the required dependencies:
   
   ```pip install -r requirements.txt```
3. Set up MongoDB and configure the connection string in the code.
   
5. Run the Flask application:
   
  ```python app.py```

## Usage

1. Access the web application in your browser at [http://localhost:8000](http://localhost:8000).

2. Enter a search query in the provided form and submit it.

3. The application will scrape images related to the query from Google search results and save them to the specified directory and MongoDB database.

## Use Cases

### Building a Image Dataset for Machine Learning

One practical use case for this image scraping project is to build a custom image dataset for machine learning tasks, such as training image classification models.

1. **Define your image categories**: Determine the classes or categories you want to include in your dataset. For example, if you're building a dataset for classifying animals, your categories might include "dog," "cat," "bird," etc.

2. **Scrape images for each category**: Use the image scraping project to search for and scrape images related to each category. Enter specific search queries for each class to retrieve relevant images.

3. **Store images in MongoDB**: The scraped images will be stored in a MongoDB database along with metadata such as the image URL and category label. You can organize your database collection by category for easier retrieval.

4. **Preprocess and annotate images**: Preprocess the scraped images as needed, such as resizing them to a uniform size or removing duplicates. You can also manually annotate the images with their corresponding class labels for supervised learning.

5. **Train and evaluate your machine learning model**: Use the annotated image dataset to train your machine learning model, such as a convolutional neural network (CNN), for image classification. Evaluate the model's performance on a separate validation or test set to assess its accuracy and generalization capabilities.

By leveraging this image scraping project, you can quickly and efficiently collect a diverse set of images for building custom image datasets tailored to your specific machine learning tasks.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or create a pull request.

