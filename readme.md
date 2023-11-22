# Gmail Autoresponder

This Node.js-based application automatically responds to emails sent to your Gmail mailbox while you're on vacation. It leverages the Gmail API to check for new emails, send replies to emails with no prior replies, and add a custom label to the processed emails.

## Features

- **Automated Responses:** The app automatically sends replies to emails that have no prior responses.
- **Labeling and Moving:** After sending a reply, the email is labeled and moved to a specified folder.
- **Randomized Intervals:** The app repeats the process at random intervals between 45 to 120 seconds.

## Getting Started

### Prerequisites

- Node.js installed
- Gmail API credentials (`credentials.json`) obtained from the [Google Cloud Console](https://console.cloud.google.com/)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/gmail-autoresponder.git
    cd gmail-autoresponder
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Run the application:

    ```bash
    node app.js
    ```

4. Follow the authorization process by visiting the provided URL and entering the code.

### Configuration

- Modify `credentials.json` with your Gmail API credentials.
- Customize the label name in `app.js` (`labelName` variable).

## Technical Details

- **Language:** Node.js
- **Dependencies:** googleapis, express
- **Authorization:** Google's local-auth library is used for authentication.
- **APIs:** Gmail API is utilized for reading and sending emails.

## Improvements

- The application could be enhanced with error handling, logging, and additional features.
- Implement more comprehensive testing to ensure robust functionality.

## Demo

[Link to Demo Video](#) - https://drive.google.com/file/d/1NLk0wm-a7G1ytg_Y_4jKk-kCC2hOXwqJ/view?usp=sharing

## Author

- Your Name
- Contact Information

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
