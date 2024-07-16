# V-Extractor

### V-Extractor is a web application that allows users to fetch and display details of a YouTube video by inputting the video link.
![image](https://github.com/user-attachments/assets/47294a31-0933-412f-adc6-119af1f025f6)

### The application uses the YouTube Data API to retrieve information such as the video title, description, thumbnail, and tags.

![image](https://github.com/user-attachments/assets/ad8e2ac1-5488-4ad3-935e-76284d0329a1)

## Features
- Fetch YouTube video details using a video link.
- Display video title, description, thumbnail, and tags.
- Easy-to-use interface.

## Prerequisites
- Java 17 or higher
- Maven 3.6.0 or higher
- Spring Boot 3.0 or Higher
- A YouTube Data API key

## Configuration
Create a file named `application.properties` in the `src/main/resources` directory with the following content:

```properties
youtube.api.key=YOUR_API_KEY
youtube.api.url=https://www.googleapis.com/youtube/v3/videos
```
