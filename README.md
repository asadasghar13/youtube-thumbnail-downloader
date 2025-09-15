# YouTube Thumbnail Downloader

A free, fast, and privacy-focused tool to download YouTube thumbnails in all available resolutions. No signup required, works completely client-side.

## Features

- **Multiple Resolutions**: Download thumbnails in maxres, SD, HQ, medium, and default sizes
- **Privacy First**: No data sent to external servers - works completely client-side
- **Fast & Responsive**: Instant thumbnail detection and download
- **Multiple URL Formats**: Supports all YouTube URL formats (youtube.com, youtu.be, shorts, etc.)
- **Copy URLs**: Easy copy-to-clipboard functionality for thumbnail URLs
- **Mobile Friendly**: Responsive design that works on all devices

## How to Use

1. Paste any YouTube URL or video ID into the input field
2. Click "Get Thumbnails" 
3. Preview all available thumbnail sizes
4. Click "Open / Download" to save the thumbnail you want
5. Use "Copy URL" to get the direct thumbnail link

## Supported URL Formats

- `https://www.youtube.com/watch?v=dQw4w9WgXcQ`
- `https://youtu.be/dQw4w9WgXcQ`
- `https://youtube.com/shorts/dQw4w9WgXcQ`
- `dQw4w9WgXcQ` (just the video ID)

## Available Thumbnail Sizes

- **Max (maxres)**: Highest quality available (1280x720)
- **SD**: Standard definition (640x480)
- **High (hq)**: High quality (480x360)
- **Medium (mq)**: Medium quality (320x180)
- **Default**: Default size (120x90)

*Note: Not all videos have maxres thumbnails available, especially older uploads.*

## Technical Details

- **Client-side only**: No server required, works offline after loading
- **No tracking**: No analytics, cookies, or data collection
- **Fast loading**: Optimized CSS and JavaScript for quick performance
- **Accessibility**: ARIA labels and keyboard navigation support

## Deployment

This is a static HTML file that can be deployed anywhere:

- **GitHub Pages**: Enable Pages in repository settings
- **Netlify**: Drag and drop the HTML file
- **Vercel**: Connect your GitHub repository
- **Any web server**: Upload the `index.html` file

## License

MIT License - feel free to use, modify, and distribute.

## Contributing

Pull requests welcome! Please ensure any changes maintain the privacy-first, client-side approach.

---

**Live Demo**: [View on GitHub Pages](https://asadasghar13.github.io/youtube-thumbnail-downloader/)