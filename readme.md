# AI Chunking

## Overview

AI Chunking is a project designed to process and divide large datasets or text into smaller, manageable chunks. This is particularly useful for applications such as natural language processing, machine learning, and data analysis, where handling large inputs efficiently is critical.

## Features

-   **Dynamic Chunking**: Automatically splits data into smaller parts based on predefined rules or custom logic.
-   **Customizable**: Supports user-defined chunking strategies for specific use cases.
-   **Scalable**: Handles large datasets efficiently without compromising performance.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/ViorelsS/ai_chunking
    ```
2. Navigate to the project directory:
    ```bash
    cd ai_chunking
    ```
3. Install dependencies:
    ```bash
    npm install
    ```

## Usage

1. Ensure you have a `podcasts.txt` file in the project directory containing the text you want to split.
2. Run the script:
    ```bash
    node index.js
    ```
3. The script will fetch the content of `podcasts.txt`, split it into chunks of 150 characters with an overlap of 15 characters, and log the output to the console.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request with a detailed description of your changes.
