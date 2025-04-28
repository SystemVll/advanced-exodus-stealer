<a href="mailto:shy-grub-swimmable@duck.com">Mail</a> | <a href="https://discord.com/users/212966578680102913">Discord</a>

```diff
- Source is not public for the moment
```

## Exodus Mnemonic Stealer Proof Of Concept
![exodus-banner](https://github.com/user-attachments/assets/b84521e4-0b16-419c-b71f-a78309c9208d)

### Overview

The Exodus Stealer Proof of Concept is a pentesting tool designed to demonstrate potential security vulnerabilities in the Exodus wallet application. This project showcases how sensitive information such as mnemonic data can be extracted from the Exodus wallet for educational and testing purposes.

### Features

-   Extracts mnemonic data from the Exodus wallet
-   Decrypts mnemonic data using a passphrase
-   Sends notifications to Discord, Telegram, or a TCP server based on configuration

![discord](https://github.com/user-attachments/assets/9c400693-ade8-448a-93e4-41d41e7c7a06)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/SystemVll/advanced-exodus-stealer.git
    ```
2. Install dependencies:
    ```bash
    bun install
    ```

### Usage

1. Modify the configuration in `.env` to specify the notification type (Discord, Telegram, TCP) and relevant details.
2. Build the payload:
    ```bash
    bun run build
    ```
3. Follow the on-screen instructions to interact with the Exodus wallet and observe the notifications sent.

### Disclaimer

This project is intended for educational and pentesting purposes only. Do not use this tool for malicious activities. The developers are not responsible for any misuse of this software.

### Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

### License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
