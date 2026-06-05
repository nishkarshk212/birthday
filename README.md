# Cinematic Birthday Surprise Project

A beautiful, cinematic web-based birthday surprise project featuring animations, music, and a memory gallery.

## Features
- 🚀 **Dynamic Landing Page**: Personalized countdown and experience based on URL parameters.
- 🛠️ **Personalization Tool**: Built-in UI to generate custom links for different people.
- ✨ Cinematic Hero Section
- 💌 Interactive Message Slider
- 💡 Celebration Stage (Interactive Lights, Music, and Balloons)
- 🎭 Dramatic Curtain Reveal
- 📸 Memory Gallery with Hover Effects
- ❤️ Floating Heart Particles

## How to Customize
You can customize this project in two ways:

### 1. Using URL Parameters (Recommended)
Simply append parameters to your URL:
- `name`: Recipient's name (e.g., `?name=John`)
- `date`: Birthday date (e.g., `?date=2026-12-25`)
- `msg`: Custom message (e.g., `?msg=Happy+Birthday+Buddy!`)
- `audio`: URL to an MP3 file

Example: `index.html?name=Riddhi&date=2026-06-05&msg=You+are+amazing!`

### 2. Using the Personalize Tool
1. Open the website.
2. Click the **"Personalize This Wish"** button at the bottom right of the landing page.
3. Fill in the details and click **"Generate Link"**.
4. Copy and share the generated link!

### 3. Manual Editing
You can still edit the `index.html` file directly:
- **Change Images**: Replace the image URLs in the Gallery Section (`gallery-grid`) with your own.

## How to Run
Simply open `index.html` in any modern web browser, or serve it using a local server:
```bash
# Example using Python
python3 -m http.server 8000
```
Then visit `http://localhost:8000`.

---
Created with ❤️ for special celebrations.
