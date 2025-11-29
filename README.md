# ✨ Brain Tumor Segmentation UI (React Frontend)

This repository contains the React single-page application (SPA) that provides a user-friendly interface for interacting with the Flask Brain Tumor Segmentation API.

## 🌟 Features

* **File Upload:** Allows users to select MRI image files (`.jpg`, `.png`, `.tif`).
* **API Integration:** Uses `axios` and `FormData` to securely transmit the image to the Flask backend.
* **Result Visualization:** Decodes the Base64 image received from the API and displays the segmented result with a multi-color overlay directly in the browser.
* **Attractive UI:** Features a modern, clean, and thematic design for a professional look.

## 📦 Prerequisites

Ensure you have Node.js and npm installed.

## 🛠️ Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone [Your-Repo-URL]
    cd [Your-Repo-Folder]
    ```

2.  **Install Node dependencies:**
    ```bash
    npm install
    ```

3.  **Add Wallpaper (Optional):** If you wish to use the generated background image, ensure `brain_network_wallpaper.jpg` is placed in the `public/` folder.

## 🚀 Running the Application

Before running the frontend, **ensure the Flask Backend is running on port 5000.**

Start the React development server:

```bash
npm start
