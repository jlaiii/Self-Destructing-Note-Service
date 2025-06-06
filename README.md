# Self-Destructing Note Service

A simple, secure, and ephemeral note-sharing service built on a decentralized network. Create secret messages that self-destruct after being read, ensuring your sensitive information remains private.

## ✨ Features

* **Self-Destructing Notes:** Notes are automatically deleted from the network after their first retrieval, ensuring ephemeral communication.
* **Optional Encryption:** Protect your notes with an AES-256 encryption key. If an encryption key is used, the note will only decrypt and self-destruct upon successful entry of the correct key.
* **Decentralized:** Built on **Gun.js**, this service leverages a peer-to-peer network, offering resilience and eliminating a central point of failure for note storage.
* **Client-Side Encryption:** All encryption and decryption happen directly in your browser. Encryption keys are never sent to the network.
* **No Accounts, No Tracking:** Absolutely no user accounts, personal data collection, or tracking.
* **Simple & Fast:** A straightforward interface for quick note creation and access.

## 🚀 Live Demo

Experience the Self-Destructing Note Service live here:
**[https://jlaiii.github.io/Self-Destructing-Note-Service/](https://jlaiii.github.io/Self-Destructing-Note-Service/)**

## 💡 Why Open Source?

This project is open source for several key reasons:

* **Transparency:** The code is fully auditable, allowing anyone to verify that encryption is done client-side, keys are not stored, and notes truly self-destruct. This builds trust, especially for a security-sensitive application.
* **Community Collaboration:** Encourages contributions, bug fixes, and feature enhancements from developers worldwide.
* **Education:** Serves as a practical example of building a decentralized web application with Gun.js and client-side encryption.
* **Freedom:** Ensures the tool remains free to use and adapt, without proprietary restrictions.

## 🛠️ Technology Stack

* **Frontend:** Pure HTML, CSS, and JavaScript
* **Decentralized Database:** **Gun.js** for peer-to-peer data storage and synchronization.
* **Encryption:** **CryptoJS** for strong client-side AES-256 encryption.

## 🧑‍💻 Development & Contribution

This is a single-file HTML application, making it incredibly easy to set up and run.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/jlaiii/Self-Destructing-Note-Service.git](https://github.com/jlaiii/Self-Destructing-Note-Service.git)
    cd Self-Destructing-Note-Service
    ```
2.  **Open `index.html`:** Simply open the `index.html` file in your web browser. That's it!

### Contributing

Contributions are welcome! If you have suggestions for improvements, bug fixes, or new features, please open an issue or submit a pull request.

## 📄 License

This project is open-sourced under the MIT License. See the `LICENSE` file (if you choose to add one) for more details.
