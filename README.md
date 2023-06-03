Certainly! Here's the combined README with the change log:

**README.md**

# VersaDecryptor 3.0

VersaDecryptor is a versatile decryptor program that supports various encryption algorithms and scenarios. It allows for the decryption of data encrypted with algorithms such as AES-256-CBC, AES-256-ECB, DES, 3DES, RSA, and more. It handles different scenarios where one or more parameters are known, including private key, IV, ciphertext, encryption algorithm, BTC address, and passphrase.

## Features

- Decrypt data encrypted with various encryption algorithms.
- Support for multiple encryption algorithms, including AES-256-CBC, AES-256-ECB, DES, 3DES, RSA, and more.
- Handle different scenarios with known parameters such as private key, IV, ciphertext, encryption algorithm, BTC address, and passphrase.
- Interactive mode for user-friendly input and decryption process.
- Retrieve and display the balances of Bitcoin addresses.
- Calculate the grand total balance of multiple Bitcoin addresses.

## Usage

1. Install Python (version 3.6 or above) on your machine.
2. Clone the repository or download the VersaDecryptor script.
3. Open a command-line interface and navigate to the directory containing the VersaDecryptor script using the `cd` command.
4. Install the required dependencies by running the command: `pip install -r requirements.txt`.
5. Run the VersaDecryptor script using the command: `python VersaDecryptor.py`.
6. Follow the prompts and provide the necessary information to decrypt the data or retrieve Bitcoin address balances.

## Change Log

### Version 2.1.1

- Added support for additional encryption algorithms, including AES-256-ECB, DES, 3DES, RSA, and more.
- Improved user experience with an interactive mode for input and decryption process.
- Enhanced Bitcoin address balance retrieval functionality.
- Added the ability to calculate the grand total balance of multiple Bitcoin addresses.
- Fixed various bugs and improved overall performance.

### Version 3.0

- Introduced multi-threading for parallel processing and improved performance.
- Added file handling functionality to decrypt entire files.
- Expanded support for other cryptocurrencies like Ethereum, Litecoin, and Ripple.
- Integrated key management features, including key generation, import, and export.
- Added support for advanced encryption modes like GCM (Galois/Counter Mode) and CTR (Counter) mode.
- Integrated blockchain explorers to fetch additional information about BTC transactions.

## Contributing

Contributions to the VersaDecryptor project are welcome! If you find any issues, have suggestions for improvements, or want to add new features, please open an issue or submit a pull request on GitHub.

## License

This project is licensed under the GNU General Public License v3.0. See the LICENSE file for more details.

## Disclaimer

This program is provided as-is, without any warranty or guarantee of its functionality or suitability for any purpose. Use it at your own risk.

---

**User's Guide**

The User's Guide provides detailed instructions on using VersaDecryptor to decrypt data and retrieve Bitcoin address balances.

**1. Decrypting Data**

To decrypt data encrypted with various encryption algorithms, follow these steps:

1. Run the VersaDecryptor script using the command: `python VersaDecryptor.py`.
2. The program will prompt you for the necessary information based on the encryption algorithm and scenario.
3. Provide the required information such as the encryption key, initialization vector (IV), and ciphertext.
4. If you have a passphrase, Bitcoin address, and ciphertext, you can enter them to derive the private key and IV for decryption.
5. The program will decrypt the data and display the decrypted result.

**2. Retrieving Bitcoin Address Balances**

VersaDecryptor allows you to retrieve and display the balances of Bitcoin addresses. Here's how to do it:

1. Run the VersaDecryptor script using the command: `python VersaDecryptor.py`.
2. Select the option to retrieve Bitcoin address balances.
3. Enter the Bitcoin address for which you want to retrieve the balance.
4. The program will fetch the balance using a blockchain explorer API and display the result.

**3. Decrypting Files**

VersaDecryptor supports decrypting entire files. To decrypt a file, follow these steps:

1. Run the VersaDecryptor script using the command: `python VersaDecryptor.py`.
2. Select the option to decrypt files.
3. Enter the path to the file you want to decrypt.
4. The program will decrypt the file and provide the decrypted result.

**4. Multi-threaded Decryption**

VersaDecryptor offers multi-threading support for parallel processing of multiple decryption tasks. To decrypt multiple ciphertexts simultaneously, follow these steps:

1. Run the VersaDecryptor script using the command: `python VersaDecryptor.py`.
2. Select the option for multi-threaded decryption.
3. Provide the necessary information for each ciphertext you want to decrypt.
4. The program will decrypt the ciphertexts concurrently, improving overall performance.

**5. Key Management**

VersaDecryptor includes key management features for generating, importing, and exporting keys. Here's how to use these features:

1. Run the VersaDecryptor script using the command: `python VersaDecryptor.py`.
2. Select the key management option (generate, import, or export).
3. Follow the prompts to generate a new key, import an existing key, or export a key to a file.

**6. Advanced Encryption Modes**

VersaDecryptor supports advanced encryption modes like GCM (Galois/Counter Mode) and CTR (Counter) mode. To use these modes, follow these steps:

1. Run the VersaDecryptor script using the command: `python VersaDecryptor.py`.
2. Select the option for advanced encryption modes.
3. Provide the necessary information for decryption using the selected mode.
4. The program will perform the decryption using the advanced encryption mode.

**7. Decrypting Other Cryptocurrencies**

In addition to Bitcoin, VersaDecryptor can handle other cryptocurrencies like Ethereum, Litecoin, and Ripple. To decrypt data related to these cryptocurrencies, follow these steps:

1. Run the VersaDecryptor script using the command: `python VersaDecryptor.py`.
2. Select the option for decrypting other cryptocurrencies.
3. Choose the specific cryptocurrency you want to decrypt (Ethereum, Litecoin, or Ripple).
4. Provide the necessary information for decryption, such as private keys or ciphertexts.
5. The program will decrypt the data and display the decrypted result.

Note: Make sure to provide accurate and valid information for decryption, as incorrect or invalid inputs may lead to incorrect results or errors.

For any further assistance or questions, please refer to the project's documentation or consult the README file on the project's GitHub repository.