# Project Overview: DSA Tracker

This project is a web-based progress tracker designed for the **NeetCode 250** curriculum. It provides a structured interface for developers to track their mastery of essential data structures and algorithms.

## 🚀 Key Features

* **Progress Persistence:** Tracks completed problems and saves your status locally.
* **Categorized Learning:** Problems are organized by topic (e.g., Arrays, Linked Lists, Trees, Graphs) to facilitate focused study sessions.
* **Resource Integration:** Direct links to problem descriptions and video solutions.
* **Modern UI:** A clean, responsive dashboard for a distraction-free coding experience.

## 🛠️ Technology Stack

The application is built using a modern, lightweight frontend stack:

* **React:** For building a component-based, reactive user interface.
* **Wouter:** A minimalist routing library for navigation.
* **Lucide React:** For consistent and scalable iconography.
* **Vite:** Used as the build tool for fast development and optimized production assets.
* **CSS Modules:** For encapsulated and maintainable styling.

## 📁 Project Structure

The repository contains the following core structure:

* `index.html`: The main entry point for the application.
* `assets/`: Contains the bundled application logic and styles.
    * `index-[hash].js`: Compiled React components and logic.
    * `index-[hash].css`: Global and component-specific styles.
* `favicon.png`: Application branding.

## 💻 Getting Started

### Prerequisites

To view or host this project, you need a modern web browser.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/neetcode-250-tracker.git](https://github.com/your-username/neetcode-250-tracker.git)
    ```
2.  **Navigate to the directory:**
    ```bash
    cd neetcode-250-tracker
    ```
3.  **Launch the app:**
    Open `index.html` in any web browser, or serve it using a local development server:
    ```bash
    # Example using Python
    python3 -m http.server 8000
    ```

## 📝 Usage

* **Checkboxes:** Click the checkbox next to a problem once you have successfully solved it.
* **Filtering:** Use the category headers to focus on specific algorithm types.
* **Reset:** Clear your progress at any time to start a new study pass.

---

