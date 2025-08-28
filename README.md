Phone Number Information Finder ☎️

This project uses the phonenumbers Python library to extract details about a given phone number.
It provides information about the geographical location and the service provider of the number.

Features

Parse international phone numbers

Identify the region (country/area) of the phone number

Retrieve the carrier/service provider name

Simple and easy-to-use script

Requirements

Python 3.7+

phonenumbers library

Installation

Clone this repository:
git clone https://github.com/yourusername/phone-number-info.git

Navigate to the project folder:
cd phone-number-info

Install dependencies:
pip install phonenumbers

Usage

Edit the script and replace the number variable with your desired phone number:
number = "+916385239041"

Run the script:
python phoneinfo.py

Example Output:
Tamil Nadu
Airtel

Code Flow

Import the phonenumbers library

Parse the given phone number

Use geocoder.description_for_number to get the location

Use carrier.name_for_number to get the service provider

Print the results

Author

Name: DANCY MABUSHA D
Email: mabushajan9@gmail.com

License

This project is licensed under the MIT License – feel free to use and modify.
