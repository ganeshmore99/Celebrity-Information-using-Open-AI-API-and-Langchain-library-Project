# Celebrity Information using Open AI API and Langchain Library

![langchain](https://github.com/ganeshmore99/Celebrity-Information-using-Open-AI-API-and-Langchain-library-Project/assets/85934803/7c5fe440-3257-422d-9ac0-e17927856599)


## Introduction
This project aims to create an application that fetches information about celebrities using the Open AI API and the Langchain library. The project is designed to be deployed on Heroku with CI/CD pipelines.

## Table of Contents

#### Introduction
#### Features
#### Setup
#### Usage
#### Contributing
#### License
#### Acknowledgements

## Features
### Fetches information about celebrities using Open AI API.
### Utilizes Langchain library for efficient data handling and processing.
### CI/CD deployment on Heroku.

## Setup
### Prerequisites
#### Python 3.8 or higher
#### Git
#### Heroku CLI
#### Open AI API Key

### Steps
Introduction and GitHub Repository Setup

#### Clone the repository:
```
git clone https://github.com/ganeshmore99/Celebrity-Information-using-Open-AI-API-and-Langchain-library-Project.git
```
### Environment Setup

#### Create a virtual environment:

```
conda create -p celeb python=3.8 -y
```

#### Install dependencies:
```
pip install -r requirements.txt
```
### Configuration

Set up environment variables for the Open AI API key:
```
export OPENAI_API_KEY='your_openai_api_key'  # On Windows use `set OPENAI_API_KEY=your_openai_api_key`
```

### Run the Application Locally

Start the application:
```
python app.py
```

### Final CI/CD Deployment on Heroku

#### Login to Heroku:

```
heroku login
```
#### Create a new Heroku application:


```
heroku create celebrity-info-app
```
#### Deploy the application:

```
git push heroku main
```
#### Set up the environment variables on Heroku:

```
heroku config:set OPENAI_API_KEY='your_openai_api_key'
```

## Usage
#### Access the deployed application on Heroku:

```
https://celebrity-info-app.herokuapp.com
```
#### Enter the name of a celebrity to fetch information.


## Contributing
Contributions are welcome! 

## License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements
Open AI API
Langchain Library
