# VersaDecryptor
This script allows for decryption of data encrypted with various encryption algorithms such as AES-256-CBC. It supports different scenarios where one or more parameters are known, including private key, IV, ciphertext, encryption algorithm, BTC address, and passphrase.
VersaDecryptor - Decryptor for various encryption algorithms

Version: 1

This script allows for decryption of data encrypted with various encryption algorithms such as AES-256-CBC.
It supports different scenarios where one or more parameters are known, including private key, IV, ciphertext,
encryption algorithm, BTC address, and passphrase.

Usage:
    python VersaDecryptor.py

Note: This is an alpha version and should be used for testing and educational purposes only. Use it responsibly
and ensure you have the necessary permissions to decrypt the data.

Feel free to copy and use this code for your development and testing purposes. Remember to add your custom code for deriving private keys, IVs, and handling other encryption algorithms as needed.
```
# VersaDecryptor

VersaDecryptor is a versatile decryption tool that supports multiple encryption algorithms and allows for the decryption of various types of encrypted data. It provides a flexible and customizable solution for decrypting encrypted files, private keys, and other sensitive data.

## Features

- Supports multiple encryption algorithms, including AES-256-CBC.
- Decrypts encrypted data using known parameters such as private key, IV, passphrase, ciphertext, or BTC address.
- Provides a command-line interface for easy usage and customization.
- Offers a modular and extensible architecture for easy integration into other projects.
- Cross-platform compatibility (Windows, macOS, Linux).

## Installation

VersaDecryptor is written in Python and requires Python 3.x to run. To install VersaDecryptor and its dependencies, follow these steps:

1. Clone the VersaDecryptor repository:

   ```
   git clone https://github.com/coelacanthtx/VersaDecryptor.git
   ```

2. Navigate to the project directory:

   ```
   cd VersaDecryptor
   ```

3. Install the required dependencies using pip:

   ```
   pip install -r requirements.txt
   ```

## Usage

To use VersaDecryptor, run the `versadecryptor.py` script with the appropriate command-line arguments. Here are some examples:

```
python versadecryptor.py --private-key <private_key> --iv <iv_value> --ciphertext <ciphertext>
```

```
python versadecryptor.py --passphrase <passphrase> --ciphertext <ciphertext> --encryption-algorithm AES-256-CBC
```

Refer to the command-line options and their descriptions in the documentation for more details on the available parameters and usage examples.

## Contributing

Contributions to VersaDecryptor are welcome! If you find any issues, have suggestions for improvements, or would like to add new features, please submit a pull request. Make sure to follow the existing coding style and include tests for any new functionality.

## License

VersaDecryptor is licensed under the GNU General Public License (GPL) v3.0. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

VersaDecryptor is built upon various open-source libraries and tools. We would like to express our gratitude to the developers of these projects for their valuable contributions.

```