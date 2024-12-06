# Story 3: Save Encrypted File

## Description

Send the encrypted note to the server and save it as a `.enc` file.

## Given, When, Then

-   **Given** a user has successfully encrypted a note,
-   **When** they click the "Encrypt and Save" button,
-   **Then** the encrypted note is sent to the server and saved as a static file.

-   **Given** the server receives the file,
-   **When** the save operation is successful,
-   **Then** a unique identifier (e.g., file name) is returned to the user.

## Acceptance Criteria

1. The encrypted note is sent to the server via an API call.
2. The server saves the file with a `.enc` extension in a predefined directory.
3. The server returns a unique identifier for the file.

## Progress

-   Current Status: To Do
