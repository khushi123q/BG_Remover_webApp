# Background Remover Web App

This Flask web application allows users to upload images and remove their backgrounds using the `rembg` library.

## Features

- Upload images in `png`, `jpg`, `jpeg`, or `webp` formats.
- Automatically process the uploaded images to remove the background.
- Display the original and background-removed images.

## Prerequisites

- Python 3.x
- Flask
- Pillow
- rembg

## Installation

1. **Clone the repository:**
   ```bash
   https://github.com/khushi123q/BG_Remover_webApp.git
   cd BG_Remover_Web.app
   ```

2. **Create and activate a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Ensure the folder structure:**
   The application will automatically create necessary directories if they don't exist:
   - `static/uploads`

## Usage

1. **Run the application:**
   ```bash
   python app.py
   ```

2. **Open your browser and navigate to:**
   ```
   http://127.0.0.1:5000/
   ```

3. **Upload an image:**
   - Choose an image file in `png`, `jpg`, `jpeg`, or `webp` format.
   - Click the "Upload" button to remove the background.

## File Structure

```
BG_Remover_webApp/
│
├── app.py                  # Main application file
├── requirements.txt        # List of required packages
├── templates/
│   └── home.html           # HTML template for the home page
└── static/
    └── uploads/            # Directory to store uploaded images
```

## Contributing

Contributions are welcome! Please create a pull request or open an issue for any changes or suggestions.

## Contact
   ```
   Email: shawkhushi10@gmail.com
   ```

