# Simple Secure Notes

**Simple Secure Notes** is a lightweight web application designed to allow users to create, encrypt, and share notes securely. It prioritizes client-side encryption, ensuring that sensitive data remains private and accessible only to those with the correct password.

---

## Features

### Core Features

-   **Create Encrypted Notes**: Users can write notes and encrypt them with a password using AES-GCM encryption.
-   **Share Notes Securely**: Generate a shareable link to the encrypted note. Only recipients with the password can decrypt and view the note.
-   **Password-Protected Note Viewing**: Recipients are prompted to enter a password when accessing a shared note.
-   **Simple UI**: User-friendly interface for creating, sharing, and viewing notes.

### Additional Features

-   **Static File Storage**: Encrypted notes are stored as static files on the server, minimizing backend complexity.
-   **Secure Encryption**: All encryption and decryption happen client-side, ensuring that sensitive data never leaves the user's device in plain text.
-   **Recipient Note Creation**: Recipients can create and share their own notes directly from the app.

---

## How It Works

1. **Create a Note**:

    - Write a note and set a password.
    - The app encrypts the note client-side.
    - The encrypted note is saved as a static file on the server.
    - A unique shareable link is generated.

2. **Share the Note**:

    - Share the link with the recipient.
    - Share the password securely through a separate channel.

3. **View the Note**:
    - The recipient opens the shareable link.
    - They enter the password to decrypt and view the note.

---

## Security

-   **Encryption**: All encryption and decryption are performed on the client-side using AES-GCM.
-   **Password Protection**: The encryption key is derived from the password, which is never stored or transmitted.
-   **Static File Storage**: Encrypted notes are saved as `.enc` files on the server.

---

## Project Management

The project follows an Agile-inspired workflow. All project management artifacts, including epics, features, and user stories, are contained within the `project-management/` folder. This structure showcases both development and project management skills.

### Workflow

-   **Epics**: High-level objectives of the project (e.g., "Encrypted Note Creation").
-   **Features**: Specific functionalities needed to achieve an epic.
-   **Stories**: Actionable, testable units that describe specific tasks within a feature.
-   **Statuses**: Tasks are organized into `to-do`, `in-progress`, and `done` directories for tracking progress.

---

## Future Enhancements

-   Add note expiration options.
-   Support for multiple languages/localization.
-   Enhanced accessibility features.
-   Integration with cloud-based file storage for scalability.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Contact

**Author**: [Your Name]  
**Email**: your.email@example.com  
**GitHub**: [yourusername](https://github.com/yourusername)
