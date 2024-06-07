# Exposed Directory Checker

This application checks for exposed directories on a list of URLs and logs the results. It can also print blocked directories and errors based on user preferences.

## Features

- Extracts directories from URLs.
- Checks if directories are exposed.
- Logs exposed, blocked, and error directories.
- Multithreaded for faster processing.

## Requirements

- Python 3.x
- `requests` library

You can install the required library using:
```sh
pip install requests
```

# Usage
- Place your list of URLs in a file named links.txt in the same directory as the script.
- Run the script.

```sh
<python path variable> exposed_directory_checker.py
```

Follow the prompts to specify if you want to print blocked directories and error links.
The results will be logged, and a file named exposed directories.txt will be created with the list of exposed directories found.