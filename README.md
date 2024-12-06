# Nahida-MD WhatsApp Bot

## 📋 Description
Nahida-MD is a WhatsApp bot built using [@whiskeysockets/baileys](https://github.com/WhiskeySockets/Baileys), designed for both personal and group interactions. The bot is modular, versatile, and easy to customize, offering an extensive set of features.

---

## 🚀 Features
- **Interactive Messages**: Dynamic carousels, buttons, and view-once messages.
- **Custom Commands**: A wide variety of preloaded commands for utilities, entertainment, and more.
- **Multimedia Handling**: Supports images, videos, stickers, and documents.
- **Easy Integration**: Modular plugins allow seamless addition of new features.
- **Secure Communication**: Built with end-to-end encryption via the WhatsApp Web API.

---

## 🛠️ Setup & Installation

### Prerequisites
Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v16 or higher)
- [Git](https://git-scm.com/)
- Termux (for Android users, optional)

### Installation Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Helo-Koshirou/Nahida-MD.git
   cd Nahida-MD
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Set Up WhatsApp Authentication**
   Run the bot to initialize the multi-file authentication system:
   ```bash
   npm start
   ```
   Scan the QR code displayed to link your WhatsApp account.

4. **Start the Bot**
   ```bash
   node index.js
   ```

---

## 📄 Usage

### Commands
- Use the prefix `.` (default) followed by a command name to interact with the bot.
- Example: `.menu` to display available commands.

### Adding Custom Plugins
- Create a new JavaScript file in the `plugins` folder.
- Define your command logic and export the configuration.
- Restart the bot to load the new plugin.

---

## 🤝 Contributing
Contributions are welcome! Whether you want to report bugs, suggest new features, or improve the codebase, feel free to participate.

### How to Contribute
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add your feature"
   ```
4. Push your changes:
   ```bash
   git push origin feature/your-feature
   ```
5. Submit a pull request.

---

## 📜 License
This project is licensed under the [MIT License](LICENSE).

---

## 👤 Author
**Helo-Koshirou**
- GitHub: [@Helo-Koshirou](https://github.com/Helo-Koshirou)
- Email: helo.koshirou@example.com

---

## 🙌 Acknowledgments
- Special thanks to [@whiskeysockets/baileys](https://github.com/WhiskeySockets/Baileys) for the powerful library.
- Inspired by the open-source community and developers worldwide.

---

## 🧰 Troubleshooting
If you face any issues, follow these steps:
1. Verify all dependencies are correctly installed.
2. Ensure your Node.js version is v16 or higher.
3. Run the bot in debug mode for detailed logs:
   ```bash
   node index.js --debug
   ```
4. Open an issue in the [GitHub repository](https://github.com/Helo-Koshirou/Nahida-MD/issues) if the problem persists.

---

### Koshirou dev
