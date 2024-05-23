# DVSA Driving Test Booking Automation

We all know that feeling: trying to book a driving test slot on the DVSA website can be a hideous, soul-crushing experience. The endless refreshing, the constant unavailability of slots, the despair... I've been there. That's why I created this project! This script automates the entire process, sparing you from the torment of finding an available test slot. Sit back, relax, and let the automation handle the chaos for you.

## Features

- Automated navigation through the DVSA driving test booking site
- Filling in driving license details, test dates, and postcodes
- Searching for test centers and fetching more centers if needed
- Random delays between actions to avoid detection
- Toast notifications for visual feedback (coming soon)
- Alert sound for audio feedback (coming soon)

## Prerequisites

- Tampermonkey or any other userscript manager
- A modern web browser (Chrome, Firefox, Edge, etc.)

## Installation

- Install the Tampermonkey extension for your browser.
- Click on the Tampermonkey extension icon in your browser and select "Create a new script".
- Copy and paste main.js and enjoy the automation.

## Usage

- Navigate to the DVSA driving test booking website: DVSA Driving Test Booking
- The script will automatically start and navigate through the booking process.
- Toast notifications will appear to indicate the progress of the automation.

## Customization

- Driving License Number: Update the drivingLicenceNumber variable with your actual driving license number.
- Test Date: Update the testDate variable with your preferred test date.
- Postcode: Update the postcode variable with your postcode.
- Instructor Reference Number: Update the instructorReferenceNumber variable if applicable.

## Disclaimer

This script is not the ultimate solution, but it's the best I could create within a limited timeframe. It is designed to automate the booking process for a standard driving test and is not configured to accommodate special needs requirements, which involve additional configurations not covered here. Feel free to copy, modify, and configure the script to suit your specific needs.

If your exam type is "car" and you don't require special needs accommodations for the exam, no extra customization is needed. Just change the placeholder values such as driving licence number, test date, postcode, or instructor reference (optional), and you are good to go.

Please note that this script is intended for educational purposes only. Use it responsibly and at your own risk.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
