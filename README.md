# MySpotify

MySpotify is an application that allows you to listen to music online using the Spotify and YouTube APIs. Additionally, it provides the ability to view song lyrics through integration with LyricsGenius. The application also allows you to download songs for offline listening.

## Main Features

- Listen to music online using the Spotify and YouTube APIs.
- View song lyrics with LyricsGenius integration.
- Download songs for offline listening.

## Requirements

To use the application, Docker must be installed on your system.

## Usage

### Building Docker Image

To create the Docker image of the application, run the following command in the project's root directory:

```
docker build -t image_name .
```

Replace `image_name` with your desired name for the Docker image.

### Running the Application

After creating the Docker image, you can run the application using the following command:

```
docker run --rm -p 8000:8000 image_name
```

The application will then be accessible at `http://localhost:8000` in your browser.

## Contributions

Contributions and suggestions to improve the application are welcome. To propose changes, please open an issue or submit a pull request.
