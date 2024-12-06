# Story 2: Implement Client-Side Encryption

## Description

Encrypt the note client-side using a password before saving.

## Given, When, Then

-   **Given** a user has written a note and entered a password,
-   **When** they click the "Encrypt and Save" button,
-   **Then** the note should be encrypted using the password.

-   **Given** a user tries to save without entering a password,
-   **When** they click the "Encrypt and Save" button,
-   **Then** they should see an error message prompting them to enter a password.

## Acceptance Criteria

1. Notes are encrypted client-side using AES-GCM.
2. The encryption key is derived from the password entered by the user.
3. If no password is entered, the save process is blocked, and an error is displayed.
