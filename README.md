# PictureRevive

## Description

PictureRevive is a Laravel application that leverages the Replicate API to restore old photos using AI. It makes use of an AI model called Codeformer. This project is perfect for experimenting and getting started with AI and Machine Learning in Laravel.

## Prerequisites

- Docker
- Laravel Sails

## Installation

### Clone the repository

```
git clone https://github.com/caleboki/PictureRevive.git
```


### Create .env file

Create an `.env` file in the root directory of the project and add your Replicate API token.

```
REPLICATE_API_TOKEN=`YOUR API TOKEN`
```

Note: You can obtain an API token from `https://replicate.com`

### Use Docker and Laravel Sails for setting up

This project uses Docker and Laravel Sails for easy setup and running. To install the project's dependencies, simply run the following command:

```
sail composer install
```

This will install all the necessary PHP dependencies. Now, you can start the server:

```
sail up
```

Now, the Laravel application should be running at [http://localhost](http://localhost).

## Usage

1. Go to [http://localhost](http://localhost).
2. You will see a UI where you can upload an old photo.
3. The application will process the photo and restore it.
4. You can download the restored photo or upload a new one.
