# Selenium-Searching-Mini-Project

This project is a **Java-based LinkedIn web scraper** that logs into LinkedIn, searches for a keyword (e.g., "hospitals"), scrapes profile names from the search results, and saves them into a CSV file.

Features

- 🔐 Logs in to LinkedIn using provided credentials
- 🔍 Searches for a keyword ("hospitals")
- 📄 Extracts names of users from search result cards
- 💾 Saves data to `output.csv`
- 🧠 Uses Selenium WebDriver with proper wait mechanisms

  

Technologies Used

- Java
- Selenium WebDriver
- ChromeDriver
- Maven (optional for dependency management)





  Setup Instructions

  1)Prerequisites

- Install [Java JDK](https://www.oracle.com/java/technologies/javase-downloads.html)
- Install [Chrome browser](https://www.google.com/chrome/)
- Download [ChromeDriver](https://chromedriver.chromium.org/downloads) compatible with your Chrome version
- (Optional) Install [IntelliJ IDEA](https://www.jetbrains.com/idea/) or [Eclipse](https://www.eclipse.org/)

  2)Configuration

- Place `chromedriver.exe` in the `drivers/` folder
- In `LinkedInScraper.java`, update the following line with your ChromeDriver path: java System.setProperty("webdriver.chrome.driver", "drivers/chromedriver.exe");




  How to Run

1) Compile the Java file: javac LinkedInScraper.java
2) Run the scraper: java LinkedInScraper
3) Check output.csv for the extracted names.



