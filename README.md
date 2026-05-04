Transliteration Accuracy Testing Project - Assignment 1
--Student Details--
Name: Jayakody J.A.K.K.

Registration Number: IT23155602

Batch: BSc (Hons) in Information Technology - Year 3 WE 1.1

--Git Link--
https://github.com/KushmiJayakody/IT23155602_ITPM_Assignment.git

--Project Description--
This project aims to assess the accuracy of the Pixelssuite Chat-Translator (Singlish to Sinhala transliteration). The test suite consists of 50 automated negative test cases developed using Playwright. It covers 24 different Singlish input types as specified in the assignment guidelines.

--Prerequisites--
Before running the tests, ensure you have the following installed on your system:
Python 3.11 or 3.12
Google Chrome browser

--Installation and Setup--
Clone this repository or extract the provided zip file.  
Open the terminal and navigate to the project directory:
  cd test_automation
Install the required Python libraries:
  pip install playwright openpyxl
Install the Playwright browsers:
  playwright install

--Running the Tests--
python IT23155602_test_automation.py --excel "IT23155602_Test_cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open
