# MyApp - Next.js Application with TypeScript

This project is a Next.js (typescript) application with ESLint and Prettier integration for enforcing coding standards.

## Prerequisites

Make sure you have Node.js and npm installed on your machine.

## Getting Started

Follow these steps to run the next.js application locally:

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/itsbharatsaini/nextjs-app.git
    ```

2. Navigate to the project directory:

    ```bash
    cd nextjs-app
    ```

4. Run the application:

    ```bash
    npm run dev
    ```

3. Build the application for production:

    ```bash
    npm run build
    npm run start
    ```
    To Run the build
    ```bash
    npm run start
    ```

## Running ESLint and Prettier

```bash
npm run lint
```
This command will display any linting errors or warnings.

```bash
npm run format
```
 It enforces a consistent style by parsing your code and re-printing it with its own rules that take the maximum line length into account, wrapping code when necessary.

## Docker image

### Build the image
 ```bash
docker build -t <image-name> .
```
Replace `<image-name>` with the desired name for your Docker image.

### Run docker container:
```bash
docker run -p 3000:3000 <image-name>
```

Once the Docker container is running, you can access the application at http://localhost:3000 in your web browser.