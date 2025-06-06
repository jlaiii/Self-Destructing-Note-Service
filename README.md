# Self-Destructing Note Service

A simple, client-side web application that allows you to create notes that self-destruct (are removed from the network) after they have been accessed and viewed. It uses a decentralized database for storage, making it resilient and censorship-resistant.

## ✨ Features

* **Ephemeral Notes:** Messages are designed to be "burn after read," meaning they are deleted from the network immediately after a recipient successfully views them.
* **Optional Encryption:** Secure your notes with an optional passphrase using AES encryption, ensuring only those with the key can decrypt and read the message.
* **Shareable Links:** Generate a unique URL for each note, which can be easily shared with intended recipients. Encryption keys can be included directly in the URL for seamless access.
* **Decentralized Storage:** Powered by [Gun.js](https://gun.eco/), notes are stored on a peer-to-peer network, eliminating the need for a central server and enhancing availability.
* **Client-Side:** All note creation, encryption, decryption, and deletion logic runs directly in the user's browser.

## 🚀 How to Use

### 1. Create a New Note

1.  Open the application in your web browser. You will see the "Create & Distribute Note" section by default.
2.  **Enter your message:** Type or paste the content of your note into the large text area.
3.  **Optional: Add an Encryption Key:** If you want to protect your note, enter a strong, memorable passphrase in the "Optional Encryption Key" field. If you leave this empty, the note will be stored unencrypted.
4.  Click the "Generate Shareable Link" button.
5.  A unique shareable link will appear below. Copy this link to share your note.

### 2. Access / View a Note

1.  To view a note, simply open the shareable link provided by the sender in your web browser.
2.  The application will automatically attempt to retrieve the note.
3.  **If the note is encrypted:** If the link includes the encryption key, the note will decrypt and display automatically. If the key is missing from the URL, you will be prompted that the note is encrypted and needs a key.
4.  **Self-Destruction:** Once the note is successfully displayed, it is immediately deleted from the network. A warning message will confirm that the note has self-destructed and will no longer be accessible if you refresh the page or leave.

### 3. Compose a New Note (After Viewing)

After viewing a note, you will see a "Compose a New Note" link. Clicking this will clear the current note view and return you to the note composition interface.

## 🔒 Security Considerations

* **Ephemeral Nature:** The core security mechanism of this service is its self-destructing nature. Once a note is viewed, it's gone from the network.
* **Client-Side Encryption:** Encryption and decryption happen entirely in your browser. This means your passphrase never leaves your device.
* **Key in URL:** For convenience, if you encrypt a note, the passphrase (encryption key) is included in the shareable URL. This is important to be aware of:
    * Anyone who gains access to the full URL will also have the key to decrypt the message.
    * Avoid sharing these URLs over insecure channels (e.g., public chat rooms, unencrypted email).
    * Your browser's history might store the URL with the key.

## 🛠️ Technologies Used

* **HTML, CSS, JavaScript:** Standard web technologies for the user interface and client-side logic.
* **Gun.js:** A peer-to-peer, decentralized, and offline-first database.
* **Crypto-JS:** A JavaScript library providing cryptographic algorithms, specifically AES for encryption/decryption in this project.

## 🚀 Future Enhancements (Ideas)

* Add an option to set a time-to-live (TTL) for notes, allowing them to self-destruct after a certain period even if not viewed.
* Implement client-side password hashing for encryption keys to avoid sending raw passphrases in the URL (though this would complicate sharing).
* Add more robust error handling and user feedback.
* Improve mobile responsiveness and overall UI/UX.

---

Feel free to fork this repository and adapt it for your needs!
