# BitCSV Generator

BitCSV Generator is a privacy-first, 100% client-side web application designed to help users quickly convert their credentials into a Bitwarden-compatible and easy-to-import CSV format.

## Features

- **100% Client-Side Processing**: All processing happens entirely within your browser. Absolutely zero data is tracked, logged, or transmitted to any server. Your sensitive information never leaves your device.
- **Easy Imports**: Generate precise CSV files ready to be imported securely into Bitwarden.
- **Auto Extract**: Paste a block of text containing credentials or a list of websites, and to let the application extract them automatically. 
- **Theme Support**: Includes light and dark mode toggles to suit your preference.
- **Same Name Toggle**: Allows you to apply one common entry name across all extracted credentials.

## Usage

1. Open `index.html` in your modern web browser.
2. Fill out the **Folder Name** if you want your credentials organized within a specific folder in Bitwarden.
3. Use the **Auto Extract** feature to quickly paste credentials (username on one line, password on the next) or use the "Add Credential" button to enter them manually.
4. Input any **Websites** and **Notes** associated with these entries.
5. Click **Generate & Download CSV** when ready. Review the security notice and download the file securely.
6. Open your Bitwarden Vault, go to Tools > Import Data, select `Bitwarden (csv)` as the format, and upload the generated CSV file.

## Disclaimer

Ensure that you keep the generated CSV files secure on your device and dispose of them permanently after confirming a successful import into Bitwarden.
