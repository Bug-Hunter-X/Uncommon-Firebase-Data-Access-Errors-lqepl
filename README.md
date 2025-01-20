# Uncommon Firebase Data Access Errors

This repository demonstrates two uncommon errors related to data access in Firebase:

1. **Accessing Snapshot Data Too Early:**  Attempting to access data from a Firebase snapshot before it's fully populated.
2. **Concurrency Issues in Transactions:**  Improper handling of concurrent transactions leading to data inconsistencies.

The `firebaseBug.js` file shows examples of these errors, while `firebaseBugSolution.js` provides the corrected implementations.

## Setup

1.  Ensure you have a Firebase project set up and initialized.
2.  Install the Firebase SDK: `npm install firebase`
3.  Configure your Firebase credentials (add your config to your firebase initialization)

## Running the code

Follow the instructions in the individual JavaScript files to run the examples.