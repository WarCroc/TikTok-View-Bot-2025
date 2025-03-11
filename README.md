# TikTok View Bot

This project is a Python script designed to **automate views**, and other tasks for TikTok videos. Using **Selenium** and other supporting libraries, it automates these processes via the [Zefoy.com](https://zefoy.com) platform.

## Features

- **Captcha Solving**: Support for CAPTCHA automation.
- **Follower Boost**: Increase followers for TikTok users. (coming soon...)
- **View Boost**: Add view counts to videos.
- **Like Boost**: Send likes to videos. (coming soon...)
- **Shares and Favorites**: Automate sharing and adding videos to favorites. (coming soon...)
- **Status Check**: Verifies process availability.

## Requirements

Before running this project, ensure the following software and libraries are installed:

- **Python 3.8+**
- **Google Chrome** (Latest version)
- **Selenium**
- **WebDriver Manager**
- Additional libraries: `time`, `datetime`, `os`, `base64`, `requests`, `colorama`, etc.

To install the required libraries, run the following command:

```bash
pip install -r requirements.txt
```

## Installation

- **Clone the Repository:**

- **Install Required Libraries:**

  ```bash
  pip install -r requirements.txt
  ```

- **Set Up WebDriver:**

  - The project uses `webdriver_manager` to automatically download and configure ChromeDriver. If Google Chrome is not installed, [download it here](https://www.google.com/chrome/).

- **Run the Script:**

  ```bash
  python main.py
  ```

---

## Usage

- When the script starts, CAPTCHA solving will begin automatically.
- Enter the video URL.
- The script will perform the processes automatically.

## Preview

https://github.com/user-attachments/assets/311a3e51-dac8-472e-b88c-eef3b8de4ecb

## Technologies Used

- **Python**: The main language of the project.
- **Selenium**: For web browser automation.
- **Requests**: To make HTTP requests.
- **Colorama**: To control console colors.

## Contribute

We welcome all contributions. If you want to add new features or resolve issues, please submit a **pull request**.

## Warnings

- This script is developed for educational purposes only. Performing actions that violate **TikTok’s terms of service and privacy policy may lead to legal consequences.** Please use responsibly.
- Zefoy.com’s functionality and CAPTCHA system may change over time. The functionality of this script is not guaranteed.

## License

This project is licensed under the **MIT License**. See the `LICENSE` file for more information.
