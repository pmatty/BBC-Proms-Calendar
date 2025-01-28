# BBC Proms Calendar

The BBC Proms has so many events that it's hard to keep track of them all! Why not create a calendar to add to your phone, computer, or internet calendar.

## Overview

This project contains a script that generates an ICS calendar file from the BBC Proms events webpage. The resulting calendar file can be imported into various calendar applications, helping you keep track of all the events easily.

## Key Features

1. **Fetch Event Data**:
    - The script makes HTTP requests to the BBC Proms events webpage to retrieve the event data.
    
2. **Parse Webpage Content**:
    - Using BeautifulSoup, the script parses the HTML content of the webpage to extract details about each event.

3. **Process and Organize Data**:
    - The extracted data is processed and organized into a structured format using pandas, including details like event titles, dates, times, and descriptions.

4. **Generate ICS Calendar File**:
    - The script uses the `ics` library to create a calendar and add events to it based on the processed data.
    - Each event in the calendar includes comprehensive details to ensure accurate representation in calendar applications.

5. **Save and Use the ICS File**:
    - The generated calendar is saved as an ICS file, which can be easily imported into calendar applications on your phone, computer, or any other device that supports ICS files.

## Usage

1. **Dependencies**:
    - Install the required libraries using pip:
      ```bash
      pip install requests beautifulsoup4 pandas ics
      ```

2. **Run the Script**:
    - Execute the script to generate the ICS file. Ensure you have an internet connection to fetch the webpage content.

3. **Import the ICS File**:
    - Once generated, import the ICS file into your preferred calendar application to view all the BBC Proms events.

## Conclusion

This tool simplifies the process of keeping track of BBC Proms events by generating a comprehensive calendar file that you can import into any calendar application. Enjoy the Proms without missing any events!
