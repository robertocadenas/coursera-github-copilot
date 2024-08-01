# Python Microservice

This project contains a Python microservice that provides addition and subtraction functionalities.

## Getting Started

To set up and use the microservice, follow these steps:

1. Clone the repository:

   ```bash
   git clone <repository_url>
   ```

2. Install the dependencies listed in the `requirements.txt` file:

   ```bash
   pip install -r requirements.txt
   ```

3. Build the Docker image:

   ```bash
   docker build -t python-microservice .
   ```

4. Run the Docker container:

   ```bash
   docker run -p 8000:8000 python-microservice
   ```

## Usage

### Addition

To perform addition, send a POST request to `/add` endpoint with the following payload:

```json
{
  "num1": 5,
  "num2": 3
}
```

The microservice will respond with the sum of the two numbers.

### Subtraction

To perform subtraction, send a POST request to `/subtract` endpoint with the following payload:

```json
{
  "num1": 5,
  "num2": 3
}
```

The microservice will respond with the difference between the two numbers.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
```

Please note that the `<repository_url>` in the instructions should be replaced with the actual URL of the repository where the project is hosted.