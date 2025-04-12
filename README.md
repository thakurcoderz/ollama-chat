# Ollama Chat

A lightweight, browser-based chat interface for interacting with your local Ollama models.

![Ollama Chat Screenshot](https://github.com/thakurcoderz/ollama-chat/raw/main/docs/screenshot.png)

## Features

- 🚀 **No installation required** - just open the HTML file in your browser
- 💬 **Chat with any Ollama model** installed on your system
- 📱 **Responsive design** - works on desktop and mobile
- 🔄 **Conversation management** - create, save, and delete conversations
- 🧠 **Model thinking** - see the model's thinking process in collapsible sections
- 🎨 **Markdown support** - format code blocks, lists, and more
- 🔍 **Model information** - view details about the selected model
- 🌡️ **Temperature control** - adjust creativity vs determinism
- 🌙 **Dark mode** - easy on the eyes
- 💾 **Local storage** - conversations are saved in your browser

## Getting Started

### Prerequisites

- [Ollama](https://ollama.ai/) installed and running on your system
- A modern web browser (Chrome, Firefox, Safari, Edge)

### Quick Start

1. Clone this repository:
   ```bash
   git clone https://github.com/thakurcoderz/ollama-chat.git
   ```

2. Open `ollama.html` in your web browser

3. Make sure Ollama is running on your system:
   ```bash
   ollama serve
   ```

4. Start chatting with your local AI models!

## Usage

### Accessing Settings

1. Click the gear icon (⚙️) in the top-right corner to open the settings panel
2. Here you can configure your connection, model parameters, and view available models
3. Click "Save & Close" to apply your changes

### Connecting to Ollama

By default, the app connects to Ollama at `http://localhost:11434`. To change this:

1. Open the settings panel
2. Enter your Ollama server URL in the "Server URL" field
3. Click "Test Connection" to verify connectivity
4. Click "Save & Close" to apply

### Selecting a Model

1. Click the model dropdown in the top-right corner
2. Select any available model from your Ollama installation
3. If you don't see your models, click the refresh button in the settings panel

### Viewing Available Models

1. Open the settings panel
2. Scroll down to the "Available Models" section
3. Here you can see all models installed on your Ollama server
4. Click "Refresh Models" to update the list

### Adjusting Model Parameters

1. Open the settings panel
2. Find the "Model Parameters" section
3. Adjust the temperature slider to control randomness (higher values = more creative, lower values = more deterministic)
4. Other parameters may be available depending on your Ollama version

### Managing Conversations

- **Create a new conversation**: Click the "New Chat" button
- **Switch between conversations**: Click on any conversation in the sidebar
- **Delete a conversation**: Click the trash icon next to a conversation

### Chat Features

- **Send a message**: Type in the input box and press Enter or click the send button
- **View model thinking**: Click on the "Model's Thinking" sections to expand/collapse
- **Format your messages**: Use Markdown syntax for formatting

## Development

This project is a single HTML file with embedded CSS and JavaScript. To modify it:

1. Edit the `ollama.html` file in any text editor
2. Refresh your browser to see changes

### Project Structure

- **HTML**: Basic structure and UI elements
- **CSS**: Styling (embedded in the `<style>` tag)
- **JavaScript**: Application logic (embedded in the `<script>` tag)

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- [Ollama](https://ollama.ai/) for making local AI models accessible
- [Tailwind CSS](https://tailwindcss.com/) for styling
- [Marked.js](https://marked.js.org/) for Markdown rendering
- [Font Awesome](https://fontawesome.com/) for icons

---

Made with ❤️ by [thakurcoderz](https://github.com/thakurcoderz)
