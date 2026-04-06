# Room AI Interior Design

Room AI Interior Design is an AI-powered architectural visualization application that transforms 2D floor plans into photorealistic 3D renders. Built with React Router 7, Tailwind CSS 4, and the Puter.js SDK.

## ⚙️ Tech Stack

- **React Router 7**: Modern full-stack React framework.
- **Tailwind CSS 4**: Utility-first CSS framework for rapid UI development.
- **Puter.js**: Infrastructure for authentication, permanent file storage, and AI model hosting.
- **Lucide React**: Beautiful icons for the interface.
- **React Compare Slider**: Side-by-side visualization of architectural transformations.

## 🔋 Features

- **2D-to-3D Visualization**: Instant rendering of flat floor plans into 3D models.
- **Persistent Media Hosting**: Publicly accessible URLs for all generated renders.
- **Project Gallery**: Personal workspace to track visualization history.
- **Side-by-Side Comparison**: Interactive tool to compare source sketches with AI renders.

## 🤸 Quick Start

### Prerequisites

- [Node.js](https://nodejs.org/en)
- [Bun](https://bun.sh/) (Recommended)

### Installation

```bash
bun install
```

### Environment Variables

Create a `.env` file in the root directory:

```env
VITE_PUTER_WORKER_URL="your_puter_worker_url"
```

### Development

```bash
bun run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

---

Built with ❤️ for architects and designers.
