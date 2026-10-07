# ▶️ Video Streaming Web Application

A responsive YouTube-style web app built with **React** and **Vite**. It pulls real, live data from the **YouTube Data API v3** to show trending videos by category, a video player page, channel info, comments and recommendations.

## ✨ Features

- Trending videos by category (Gaming, Sports, Music, Tech, News and more)
- Collapsible sidebar, just like YouTube
- Video page with embedded player, views, likes and publish time
- Channel details with subscriber count
- Expandable video description ("Read More / Read Less")
- Top comments with author, avatar and likes
- Recommended videos beside the player
- Client-side routing with React Router

## 🛠️ Tech Stack

React 18 · Vite · React Router · Moment.js · YouTube Data API v3 · CSS

## 🚀 Getting Started

1. Clone the repo and install dependencies:
   ```bash
   git clone https://github.com/manabchanda2000/Video-Streaming-Web-Application.git
   cd Video-Streaming-Web-Application
   npm install
   ```
2. Get a free API key from the [Google Cloud Console](https://console.cloud.google.com/) (enable **YouTube Data API v3**).
3. Create a `.env.local` file in the project root:
   ```
   VITE_YT_API_KEY=your_api_key_here
   ```
4. Start the dev server:
   ```bash
   npm run dev
   ```

Other scripts: `npm run build` (production build) · `npm run preview` · `npm run lint`

## 📁 Structure

```
src/
├── Components/   # Navbar, Sidebar, Feed, PlayVideo, Recommended
├── Pages/        # Home, Video
├── assets/       # Icons and images
└── data.js       # API key + helper to format view counts
```

## 🔮 Future Improvements

- Working search bar
- Subscribe, like and save actions
- Dark mode and infinite scroll

## 👨‍💻 Author

**Manab Chanda** – [GitHub](https://github.com/manabchanda2000)
