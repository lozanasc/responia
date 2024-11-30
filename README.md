# Responia

🚀 Browser extension that brings AI-powered email assistance directly into your inbox. Stop context-switching between email and AI tools - get intelligent response suggestions right where you write.

## Features

- 📧 Seamless integration with Gmail & Outlook
- 💡 Real-time, contextual email reply suggestions
- 🎨 Customizable writing styles and tone
- 🔒 Privacy-focused design
- ⚡ Zero-latency composition assistance
- 🎯 Personal context awareness

## Installation

### For Users
1. Visit the Chrome Web Store (coming soon)
2. Click "Add to Chrome"
3. Grant necessary permissions
4. Start using Responia in your email client

### For Developers
```bash
# Clone the repository
git clone https://github.com/yourusername/responia.git

# Navigate to project directory
cd responia

# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build
```

## Usage

1. **Setup**: After installation, click the Responia icon to configure your preferences:
   - Set your name and role
   - Choose your preferred writing style
   - Customize additional settings

2. **Writing Emails**: 
   - Open your email compose window
   - Start writing or click the Responia button
   - Get real-time suggestions based on context
   - Click to apply suggestions

3. **Customization**:
   - Adjust writing style on the fly
   - Save common phrases
   - Configure response preferences

## Development

### Prerequisites
- Node.js 16+
- npm or yarn
- Chrome browser

### Tech Stack
- React 18
- TypeScript
- Vite
- Tailwind CSS
- Chrome Extension Manifest V3

### Project Structure
```
responia/
├── src/
│   ├── components/      # React components
│   ├── content/         # Content script
│   ├── background/      # Service worker
│   ├── popup/          # Extension popup
│   └── utils/          # Utilities
├── public/             # Static assets
└── ...config files
```

### Building and Testing

```bash
# Watch mode for development
npm run watch

# Production build
npm run build

# Run tests
npm run test
```

### Loading the Extension
1. Build the project
2. Open Chrome and navigate to `chrome://extensions/`
3. Enable "Developer mode"
4. Click "Load unpacked"
5. Select the `dist` directory

## Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Privacy

Responia is designed with privacy in mind:
- No email content is stored
- All processing happens locally
- Minimal data collection
- Transparent data handling

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support

- 📚 [Documentation](docs/README.md)
- 🐛 [Issue Tracker](https://github.com/yourusername/responia/issues)
- 💬 [Discussions](https://github.com/yourusername/responia/discussions)

## Acknowledgments

- Thanks to all contributors
- Built with [Chrome Extension Boilerplate](https://github.com/lxieyang/chrome-extension-boilerplate-react)
