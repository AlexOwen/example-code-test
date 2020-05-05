Attention: this repository is unmaintained and incomplete. It is an example only and not for use anywhere important.

# Example Code Test

This project was written for a code test I completed recently.

The brief was to create a React-based form with three fields, one of which gets data from the backend to populate it. The project should have an API and basic error checking/testing. There should also be a second page which shows all previous responses entered into the form.

Is it perfect? No, not by any means. It took about 3 hours and is a basic express/mongoDB API with a create-react-app based front end. Please see the [GitHub Issues](https://github.com/AlexOwen/example-code-test/issues) for the improvements it desperately needs.

## Overview

This is a short form which requests details from a user, saves them to a database, and displays all the saved data.

## Installation

This application requires:

- Node v13.11.0 (may work on older versions)
- npm or yarn
- MongoDB v4.2 (may work on older versions)

### Install dependencies

`npm install` for both the front end and back end applications.

## Usage

- Ensure MongoDB is running on localhost using the default port.
- To run the application, `npm start` from the back end folder and separately from the front end folder.

**Note** The react application runs in debug/development mode.

## Testing

`npm test` from either the front or back end folder.

## Notes

- The front end is based on create-react-app and should behave exactly as expected.
- The back end is an express based application and generally follows normal conventions.

## Troubleshooting

Please email or call me if you have any issues, I have tried it several times and *it works on my machine*.

## Suggestions/Improvements

Please refer to the [GitHub Issues](https://github.com/AlexOwen/example-code-test/issues) section for this project.