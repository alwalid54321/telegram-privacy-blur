# Telegram Web Privacy Blur

A browser extension that enhances privacy by automatically blurring Telegram Web chats when you're not actively using them.

## Features

- 🔒 **Automatic Privacy Protection**: Blurs chat content when you switch tabs or are inactive
- ⚡ **Quick Toggle**: Easily enable/disable the blur feature with a single click
- 🎨 **Customizable**: Adjust blur intensity and activation delay to your preference
- 🧩 **Lightweight**: Minimal impact on browser performance
- 🌐 **Works on Multiple Platforms**: Compatible with Chrome, Firefox, and Edge

## Installation

### Chrome Web Store
*Coming soon*

### Manual Installation
1. Download the latest release from the [Releases](https://github.com/alwalid54321/telegram-privacy-blur/releases) page
2. For Chrome/Edge:
   - Go to `chrome://extensions/` or `edge://extensions/`
   - Enable "Developer mode"
   - Click "Load unpacked" and select the downloaded extension folder
3. For Firefox:
   - Go to `about:debugging#/runtime/this-firefox`
   - Click "Load Temporary Add-on"
   - Select any file in the downloaded extension folder

## Usage

1. Install the extension
2. Navigate to [Telegram Web](https://web.telegram.org/)
3. The extension will automatically blur your chats when:
   - You switch to another tab
   - Your browser window loses focus
   - You're inactive for the set period

## Development

### Prerequisites
- Node.js (14.x or newer)
- npm or yarn

### Setup
```bash
# Clone the repository
git clone https://github.com/alwalid54321/telegram-privacy-blur.git
cd telegram-privacy-blur

# Install dependencies
npm install
# or
yarn install

# Build the extension
npm run build
# or
yarn build
```

### Project Structure
```
telegram-privacy-blur/
├── src/
│   ├── content/         # Content scripts
│   ├── background/      # Background scripts
│   ├── popup/           # Extension popup UI
│   └── utils/           # Utility functions
├── public/              # Static assets
└── manifest.json        # Extension manifest
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Privacy

This extension does not collect or transmit any user data. All functionality is processed locally in your browser.