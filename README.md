# Postman to K6

This repository contains scripts for converting Postman collections to K6 scripts.

## Installation

### Global Installation

1. Install Node.js and npm if they are not already on your machine.
    ```bash
    sudo apt install nodejs npm
    ```

2. Install the postman-to-k6 package globally.
    ```bash
    npm install -g @apideck/postman-to-k6
    ```

### Local Installation

1. Navigate to your project directory.
    ```bash
    cd /path/to/your/project
    ```

2. Install the postman-to-k6 package locally.
    ```bash
    npm install @apideck/postman-to-k6
    ```

## Usage

### Conversion with Collection Only

1. Convert your Postman collection to a K6 script.
    ```bash
    npx postman-to-k6 YOUR_POSTMAN_COLLECTION.json -o YOUR_K6_SCRIPT.js
    ```

### Conversion with Collection and Environment Variables

1. Convert your Postman collection to a K6 script, including environment variables.
    ```bash
    npx postman-to-k6 YOUR_POSTMAN_COLLECTION.json -e YOUR_ENV_FILE.json -o YOUR_K6_SCRIPT.js
    ```

2. Run your K6 script.
    ```bash
    k6 run YOUR_K6_SCRIPT.js
    ```

## Contributing

Please read CONTRIBUTING.md for details on our code of conduct, and the process for submitting pull requests to us.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details

## Official Documentation

For more information, please refer to the [official documentation](https://www.npmjs.com/package/@apideck/postman-to-k6).