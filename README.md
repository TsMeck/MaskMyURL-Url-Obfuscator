# MaskMyURL - URL Obfuscation Script

This Python script is a tool that obfuscates (hides) a user-provided URL in various ways and saves it to a file. It primarily uses open redirect mechanisms to achieve this. It can be particularly useful for phishing tests, cybersecurity awareness training, and ethical hacking.

## How to Use

### 1. Requirements
To run this script, you need Python installed on your computer.
- Python 3.x

If you don't have Python installed, you can download it [here](https://www.python.org/downloads/).

### 2. Running the Script
You can run the script using a terminal or command prompt.

1. Open a terminal or command prompt.
2. Navigate to the script's directory:
   ```sh
   cd /script_directory
   ```
3. Run the script:
   ```sh
   python script.py
   ```
4. The program will prompt you to enter a URL. Example:
   ```
   Enter url: https://example.com
   ```
5. The program will generate obfuscated URLs and save them in `url_obfuscated.txt`.

## How It Works

1. The script takes a URL input from the user.
2. It obfuscates the URL using open redirect mechanisms.
3. It applies HTTP Basic Authentication tricks to further obfuscate the URL.
4. All obfuscated URLs are written to `url_obfuscated.txt`.

## Main Components

- **`get_url()`**: Gets a URL from the user and ensures it has an HTTP/HTTPS prefix.
- **`file_w()`**: Combines the URL with open redirect links and writes them to a file.
- **`http_basic_auth()`**: Obfuscates the URL using HTTP Basic Authentication formatting.

## Generated Files

After running the script, the following file will be created:
- **`url_obfuscated.txt`**:
  - Contains various obfuscated versions of the input URL.
  - Can be used for phishing and security testing purposes.

## Warnings
- **This script is for ethical hacking and security testing only!** Unauthorised use is illegal.
- Be cautious, as open redirects can pose security risks.
- Firefox does not support the HTTP Basic Authentication obfuscation technique.

## Contributing

If you would like to contribute to this project, please leave a star in the repo.

## Disclaimer

This project is intended solely for educational purposes.

## License
This project is licensed under the **MIT License**. See the `LICENSE` file for details.

