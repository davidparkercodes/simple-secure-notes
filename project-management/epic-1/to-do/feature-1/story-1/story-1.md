# Story 1: Create Note-Writing UI

## Description

Create a text area for users to write their notes, with basic validation (e.g., max length 500 characters).

## Given, When, Then

-   **Given** a user is on the note creation page,
-   **When** they type into the text area,
-   **Then** they should see their input displayed.
-   **Given** a user enters more than 500 characters,
-   **When** they try to save the note,
-   **Then** they should see an error message.

## Acceptance Criteria

1. A text area is visible on the page.
2. Users can input and edit text.
3. The text area enforces a maximum length of 500 characters and displays a validation error if exceeded.
