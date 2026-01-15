# 🧠 AI-Powered Mind Map Generator

A powerful, interactive web tool that transforms any topic, text, or idea into a structured mind map instantly using **Google Gemini AI**. Built with speed and aesthetics in mind.

<video src="public/Mind Map Generator.mp4" controls width="100%" autoplay loop muted></video>

## ✨ Features

- **Instant Visualization**: Just type a topic or paste a summary, and watch the structure unfold in seconds.
- **Powered by Gemini 2.0**: Leverages Google's latest `gemini-2.0-flash-exp` model for deep understanding and logical structuring.
- **Interactive Maps**: Fully zoomable and pannable mind maps powered by `markmap-view`.
- **Premium UI**: A sleek, modern dark-mode interface built with Tailwind CSS, featuring glassmorphism and smooth animations.
- **Privacy Focused**: Your API key is stored locally in your browser so you don't have to re-enter it, and is never sent to our servers (only directly to Google).
- **Responsive Design**: Works on desktop and large tablets for productive brainstorming sessions.

## 🛠️ Technology Stack

- **Framework**: [Astro](https://astro.build/) - For high-performance static rendering and easy component management.
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) - For rapid, beautiful, and responsive styling.
- **AI Model**: [Google Gemini API](https://ai.google.dev/) (`gemini-2.0-flash-exp`) - For generating the structured content.
- **Visualization**: [Markmap](https://markmap.js.org/) - For rendering the interactive SVG mind maps.

## 🚀 Getting Started

### Prerequisites

- Node.js (v18.17.1 or higher)
- npm (v9.6.7 or higher)
- A **Google Gemini API Key**. You can get one for free [here](https://aistudio.google.com/app/apikey).

### Installation

1.  **Clone the repository** (or download usage):

    ```bash
    git clone https://github.com/nicolas-deyros/mind-map-generator.git
    cd mind-map-generator
    ```

2.  **Install dependencies**:

    ```bash
    npm install
    ```

3.  **Start the development server**:

    ```bash
    npm run dev
    ```

4.  **Open your browser**:
    Navigate to `http://localhost:4321` to see the app in action.

## 📖 How to Use

1.  **Enter API Key**: On the sidebar, paste your Google Gemini API Key. It will be saved securely in your browser's local storage for future sessions.
2.  **Input Topic**: In the text area, type a topic (e.g., "History of the Roman Empire") or paste a block of text (e.g., meeting notes, book summary) that you want to visualize.
3.  **Generate**: Click the **"Generate Mind Map"** button.
4.  **Interact**:
    - **Zoom/Pan**: Use your mouse wheel to zoom and click-drag to pan around the map.
    - **Collapse/Expand**: Click on any node circle to collapse or expand its branches.

## 💡 Use Cases

- **Study & Learning**: Quickly break down complex subjects into key concepts.
- **Project Planning**: Visualize project structures, tasks, and dependencies.
- **Content Creation**: Outline blog posts, videos, or presentations.
- **Meeting Summaries**: Turn messy meeting notes into a clear, actionable hierarchy.

## 🤝 Contributing

Contributions are welcome! If you have suggestions or improvements, please fork the repo, create a feature branch, and submit a Pull Request.

---

_Built with ❤️ by [Nicolas Deyros](https://github.com/nicolas-deyros)_
