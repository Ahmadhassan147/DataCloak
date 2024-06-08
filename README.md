# 🖼️🔒 DataCloak: Image Steganography with LSB Substitution and Encryption

## Overview

DataCloak is an advanced image steganography project that utilizes the Least Significant Bits (LSB) substitution method to hide encrypted data within an image. By combining encryption and steganography, DataCloak ensures that the hidden data is imperceptible to the human eye and secure from unauthorized access. Additionally, DataCloak evaluates the performance of the steganography process using Peak Signal-to-Noise Ratio (PSNR) and Mean Squared Error (MSE) metrics.

## Features

- **🔐 Data Encryption:** Encrypts the data before embedding to enhance security.
- **🖼️ LSB Substitution:** Embeds the encrypted data into the image with minimal perceptible changes.
- **📊 Performance Metrics:** Calculates PSNR and MSE to evaluate the quality and fidelity of the steganography process.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following requirements:

- MATLAB

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/image-steganography.git
    cd image-steganography
    ```

2. Open MATLAB and navigate to the project directory.

### Usage

1. **Run the Script:**
    - Open MATLAB and execute the main script (`main.m`). The script will prompt you to select the carrier and secret images, perform encryption, embedding, and extraction, and display the results.

2. **Step-by-Step Process:**
    - **Select Carrier and Secret Images:** Use the GUI prompts to select the images.
    - **Encryption:** The secret image is encrypted using a randomly generated key.
    - **Embedding:** The encrypted image is embedded into the carrier image using LSB substitution.
    - **Extraction:** The encrypted image is extracted from the steganographic image.
    - **Decryption:** The extracted image is decrypted to reveal the original secret image.

3. **Performance Metrics:**
    - **PSNR (Peak Signal-to-Noise Ratio):** Measures the quality of the steganography process. Higher PSNR indicates better quality.
    - **MSE (Mean Squared Error):** Measures the average squared difference between the original and steganographic images. Lower MSE indicates better quality.


## Performance Metrics

- **PSNR (Peak Signal-to-Noise Ratio):** Used to measure the quality of the steganography process. A higher PSNR value indicates better quality.
- **MSE (Mean Squared Error):** Measures the average squared difference between the original and steganographic images. A lower MSE value indicates better quality.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any improvements.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/YourFeature`)
3. Commit your Changes (`git commit -m 'Add some feature'`)
4. Push to the Branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

Ahmad Hassan - [ahmad.hassan.hnd2003@gmail.com](mailto:your-email@example.com)

Project Link: [[https://github.com/Ahmadhassan147/DataCloak](https://github.com/Ahmadhassan147/DataCloak)]

