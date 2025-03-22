# ColorPaletteAI-Project

ColorPaletteAI-Project is a Python-based application that leverages the OpenAI API to generate color palettes based on text input. The project runs on a Flask server, allowing users to input prompts and receive AI-generated color schemes.

## Features
- Generate color palettes based on text descriptions
- Uses OpenAI API for intelligent color selection
- Simple and intuitive UI with a clean design
- Built with Flask for easy server usage

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/ColorPaletteAI-Project.git
   cd ColorPaletteAI-Project
   ```

2. Create and activate a virtual environment:
   ```sh
   python3 -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

4. Create a '.env' file in the root directory to store your OpenAI API Key. Use the below convention:
   ```sh
   OPENAI_API_KEY=[your-api-key-here]
   ```

7. Run the Flask server:
   ```sh
   flask run
   ```

8. Open your browser and navigate to the specified port:
   ```
   http://127.0.0.1:5000
   ```

## Usage

- Enter a text prompt (e.g., "Google brand colors").
- Click "Generate" to receive a matching color palette.
- The background updates with the generated colors, displaying their hex values.
- The color tiles can be clicked on to be copied to your clipboard.

## Screenshots

### Initial Interface
![Initial Screen](Screenshot%202025-03-21%20at%208.59.51%E2%80%AFPM.png)

### Generated Color Palette Example
![Generated Palette](Screenshot%202025-03-21%20at%209.00.06%E2%80%AFPM.png)

## Technologies Used
- **Python** - Backend logic
- **Flask** - Web framework
- **OpenAI API** - AI-powered color generation
