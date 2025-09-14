# Proxy-Checking-Ipify
A Python script designed to check, filter, and score proxies

A powerful Python-based proxy checker that goes beyond simple validation. This script evaluates proxy quality by testing for liveness, measuring latency, and assigning a performance score. Key features include:
-Live Check: Quickly determines if a proxy is active and reachable.
-Proxy Scoring: Ranks proxies based on their speed and reliability.
-Geographic Filtering: Allows you to filter proxies by specific countries and cities, ensuring you find the right proxies for your needs.
This tool helps you build and maintain a list of high-quality, reliable proxies, saving you time and improving the efficiency of your web scraping or data-gathering tasks.

# Usage

1.  **Create a file** named `proxies.txt` in the same directory as the script.
2.  **Add your proxies** to the `proxies.txt` file, with each proxy on a new line. The format should be `IP:Port`.
    ```
    123.45.67.89:8080
    98.76.54.32:3128
    ```
3.  **Run the script** from your terminal using the following command:
    ```bash
    python bot.py
    ```

The script will then read your proxies, check their status, score them, and provide the results.
