# Random Word Selector Utility

The Random Word Selector Utility is a small .NET command-line tool designed to provide random words and their translations from a text file. This utility is useful for language learning or any scenario where you need a quick and random selection of words.

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Prerequisites](#prerequisites)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Configuration](#configuration)
7. [Contributing](#contributing)
8. [License](#license)

## Introduction

Learning new words can be more enjoyable when presented randomly. This utility aims to facilitate language learning or other scenarios where a random selection of words and their translations is beneficial.

## Features

- **Random Word Selection:** Provides a random word and its translation from a text file.
- **Easy Integration:** Simple command-line interface for quick access.

## Prerequisites

- **.NET SDK:** Ensure that you have the .NET SDK installed on your machine. If not, you can download it [here](https://dotnet.microsoft.com/download).

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/random-word-selector-utility-dotnet.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd random-word-selector-utility-dotnet
    ```

3. **Build the Solution:**

    ```bash
    dotnet build
    ```

## Usage

1. **Run the Utility:**

    ```bash
    dotnet run --wordFile /path/to/word/file.txt
    ```

    - Replace `/path/to/word/file.txt` with the path to your text file containing words and translations.

2. **Review Results:**

    The utility will output a random word and its translation from the specified file.

## Configuration

The utility uses command-line arguments for configuration. The key argument is:
   - `--wordFile`: The path to the text file containing words and translations.

## Contributing

Contributions are welcome! If you have additional features, improvements, or bug fixes, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). See the LICENSE file for details.

Happy learning with random words!
