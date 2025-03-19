# WhatsApp Chat Viewer

This project is a web-based application designed to display exported WhatsApp chat files (`.txt`) in a clean, chat-like interface. The interface mimics the familiar WhatsApp layout and includes media support.

## Features
✅ Loads WhatsApp chat `.txt` files directly in the browser.  
✅ Mimics WhatsApp's chat layout with distinct sender bubbles.  
✅ Supports media display (images, videos) and file downloads.  
✅ Optimized for performance with **infinite scrolling** to reduce memory usage.  
✅ Lightweight, no external libraries required.  

## Usage Instructions
1. Open `index.html` in your browser.  
2. Click on the **"Choose File"** button and select your `.txt` file.  
3. Ensure media files are kept in the same folder as the `.txt` file for proper display.  

## How It Works
1. Click the **"Choose File"** button and select a `.txt` file exported from WhatsApp.  
2. The app initially loads **100 messages** for faster performance.  
3. As you scroll down, additional messages are loaded automatically in batches of **100**.  
4. Media files (images, videos, etc.) are displayed if they are available in the same folder as the `.txt` file.  

## Folder Structure
```
📂 Project Folder
 ├── index.html       # Main HTML file (UI & logic)
 ├── chat.txt         # Sample WhatsApp chat file (for testing)
 ├── image1.jpg       # Sample media file (must match filename in .txt)
 ├── video1.mp4       # Sample video file (must match filename in .txt)
 └── README.md        # This documentation file
```

## Sample File Format
```
22/04/2024, 20:21 - Rahul: Hello!
22/04/2024, 20:23 - You: Hi Rahul! How are you?
22/04/2024, 20:25 - Rahul: image1.jpg (file attached)
22/04/2024, 20:28 - You: That's great!
```

## Known Limitations
- Media files **must** be placed in the same folder as the `.txt` file.  
- Only `.jpg`, `.png`, `.jpeg`, `.gif`, `.mp4`, `.webm`, and `.ogg` are supported for inline display.  
- Large chat files may take time to parse if they exceed several MBs.  

## Future Improvements (I'm Not Sure)
🚀 Add support for date-based search.  
🚀 Improve UI with more interactive elements.  
🚀 Add theme customization options.  

## Contributing
Contributions are welcome! Feel free to submit issues, suggestions, or pull requests.

## License
This project is licensed under the [MIT License](LICENSE).
