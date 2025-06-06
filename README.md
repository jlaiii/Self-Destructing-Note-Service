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

---

## ⚖️ Usage and Licensing - **STRICTLY PERSONAL, NON-COMMERCIAL USE ONLY**

This project is provided free of charge strictly for **personal, non-commercial purposes**. Please read the terms below carefully, as any deviation requires explicit written permission from the copyright holder.

**You ARE Permitted To:**

* Use this software for your own private, individual, non-commercial projects and personal learning.
* Study, modify, and adapt the code for your personal use.
* Share the software with others for their personal, non-commercial use, **provided this entire license is included and explicitly communicated with every copy.**

**You are STRICTLY PROHIBITED From:**

* **Commercial Use/Profit:** You **cannot** use, incorporate, or integrate this software into any product, service, or activity that aims to generate direct or indirect financial profit, revenue, or commercial gain. This explicitly includes, but is not limited to:
    * Selling the software, or any derivative works based on it.
    * Licensing the software for a fee.
    * Using the software to provide paid services.
    * Embedding the software into commercial applications, websites, or platforms.
    * Any form of monetization (e.g., advertising, subscription fees, donations) directly related to the distribution or use of the software.
* **Unauthorized Redistribution:** You **cannot** redistribute, share, or make the software publicly available on any platform or medium if such redistribution enables commercial use by others, or if it implies a license broader than "personal, non-commercial use."
* **Claiming Authorship:** You **cannot** claim sole authorship or ownership of the original software. The original copyright notice must remain intact.

This license ensures transparency regarding the code's functionality and security practices for personal users, while explicitly reserving all commercial rights.

---

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

If you have suggestions for improvements or bug fixes, please open an issue or submit a pull request. Contributions are welcome, provided they strictly adhere to the personal, non-commercial use terms of the project's license.

## 📄 License

This project is licensed under a **custom license that permits personal, non-commercial use only**. Please see the `LICENSE` file for the full, detailed terms and conditions.
