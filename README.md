# News Demo

### This project was done following this awesome [Tutorial](https://freshman.tech/web-development-with-go/)

<br>
<br>
<br>

This is a simple Go project designed to test the capabilities of the Go HTTP router by fetching news from an external API endpoint. The project demonstrates the basic structure of a Go application, showcases how to set up routing using the HTTP router, and performs API requests to retrieve news data.

## Project Structure

The project structure is organized as follows:

```plaintext
golang-h
│
├── assets/
|   └─── style.css
├── main.go
├── news/
│   └─── news.go
│
└── README.md
```

- **main.go**: The entry point of the application where the server is initialized.
- **assets/**: Contains the static files (css)
- **news/**: Contains handles logic for fetching data
- **README.md**: This file, providing an overview of the project.

## Usage

To run the project, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/unkletayo/news-demo.git
   ```

2. Navigate to the project directory:

   ```bash
   cd news-demo
   ```

3. Install any required dependencies:

   ```bash
   go mod download
   ```

4. Run the application:

   ```bash
   go run main.go
   ```

5. Access the API by opening a web browser or using a tool like [curl](https://curl.se/) or [Postman](https://www.postman.com/). The API endpoints are defined in the `router.go` file.

## API Endpoints

- `/search?q={id}`: Retrieves a specific news article by its ID from the external API.

## Contributing

Feel free to contribute to this project by opening issues, submitting pull requests, or adding additional features to enhance its functionality.

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/git/git-scm.com/blob/main/MIT-LICENSE.txt) file for details.

---
