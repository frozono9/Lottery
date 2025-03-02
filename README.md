# Lottery

# Lotto Whisper - Lottery Checker

## Overview
Lotto Whisper is a web-based lottery checking application that allows users to verify their lottery numbers against winning numbers. The application features a clean, modern interface with responsive design for optimal viewing on different devices.

## Features

### Core Functionality
- **Number Checking**: Enter a 5-digit lottery number to check if it's a winner
- **Results Display**: View immediate feedback on whether your number has won
- **Recent Winners List**: Browse through paginated list of recent lottery winners
- **Hot/Cold Numbers**: View a visual display of frequently drawn numbers

### User Interface
- Responsive design that works on desktop and mobile devices
- Clean, modern UI with interactive elements
- Animated transitions and loading states
- Color-coded feedback for winning/non-winning numbers

### Administrative Features
- Admin settings panel (accessible via footer button)
- Ability to force specific winning numbers
- Customizable winner information
- Adjustable "magic sum" for hot/cold number generation

## Technical Details

### Algorithm
The application uses a specific algorithm to determine winning numbers:
1. The input number is reversed
2. Each digit is subtracted from 10 (with 0 remaining 0)
3. The resulting number is compared with the input to determine winning status

### File Structure
- Single HTML file containing all necessary code
- Inline CSS for styling
- Vanilla JavaScript for functionality
- No external dependencies except Font Awesome (loaded via CDN)

### Technologies Used
- HTML5
- CSS3 (with CSS variables, flexbox, and grid)
- JavaScript (ES6+)
- Font Awesome icons
- Web animations API

## Usage

### General User
1. Navigate to the website
2. Enter your 5-digit lottery number in the "Check Number" section
3. Click "Check My Number" or press Enter
4. View the results and whether your number is a winner
5. Browse recent winners and hot/cold numbers for reference

### Admin Usage
1. Click the "Admin Settings" button in the footer
2. Modify the following settings as needed:
   - Forced Winner Name
   - Forced Winning Number (5 digits)
   - Forced Winner Date (MM/DD/YYYY format)
   - Forced Prize Amount
   - Magic Square Sum (18-136)
3. Click "Save Settings" to apply changes

## Customization
The application offers several customization options:
- Color scheme can be modified by changing CSS variables in the `:root` selector
- Jackpot amount is randomly generated but can be modified in the JavaScript
- Winner list data is generated dynamically but can be replaced with real data
- Hot/Cold numbers display can be adjusted via the Magic Square Sum setting

## Implementation Notes
- The application simulates a lottery checking service using client-side JavaScript
- No server-side processing or database is required
- The "winning" algorithm is deterministic based on the input number
- A responsive design ensures usability across devices

## Future Enhancements
Potential improvements for future versions:
- User accounts and saved numbers
- Multiple lottery game support
- Historical drawing data
- Statistics and probability calculators
- Email notifications for drawing results
- Enhanced mobile app version

## License
© 2025 Lucky Numbers. All rights reserved.
