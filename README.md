# Gothic Valentine's Day Website 🖤🥀

A darkly romantic Valentine's Day website with an interactive envelope, music integration, and gothic aesthetics.

## Features

- **Interactive Envelope**: Click to open and reveal the Valentine's message
- **Yes/No Choice**: The "Yes" button grows bigger each time "No" is clicked
- **Music Integration**: Songs play at specific moments and on hover
- **Gothic Design**: Dark romantic theme with rose petals and elegant typography
- **Two Pages**: Envelope page and romantic quote page with song boxes

## Setup Instructions

### 1. Download the Files
You should have two HTML files:
- `index.html` (the envelope page)
- `love-letter.html` (the quote and song boxes page)

### 2. Music Integration
**Good news!** The songs are already integrated via YouTube. No need to download MP3 files! The website uses YouTube's embedded player to play the songs:

**Songs included:**
- Bury Me Deep Inside Your Heart - HIM
- Demolition Lovers - My Chemical Romance
- Lonely Day - System of a Down
- Lovesong - The Cure
- Sacrifice - London After Midnight
- Be Quiet and Drive (Far Away) - Deftones

**Note:** The YouTube videos play in the background (no video visible, audio only).

### 3. Upload to GitHub

1. Create a new repository on GitHub
2. Name it whatever you want (e.g., `gothic-valentine`)
3. Upload the two HTML files:
   - `index.html`
   - `love-letter.html`

4. Enable GitHub Pages:
   - Go to repository Settings
   - Scroll to "Pages" section
   - Under "Source", select your main branch
   - Click Save
   - Your site will be live at: `https://yourusername.github.io/gothic-valentine/`

### 4. Customization Options

**Change the name "Jay":**
In `index.html`, find this line:
```html
<span class="name">Jay</span>
```
Replace "Jay" with your boyfriend's name.

**Modify the quote:**
In `love-letter.html`, edit the quote section to personalize the message.

**Change colors:**
Edit the CSS variables at the top of each HTML file:
```css
:root {
    --blood-red: #8b0000;
    --rose-red: #c41e3a;
    /* etc. */
}
```

## How It Works

### Page 1 (index.html):
1. Visitor sees a closed red envelope
2. Click to open it
3. "Bury Me Deep Inside Your Heart" starts playing
4. Letter slides out asking "Will you, Jay, be my Valentine?"
5. Clicking "No" makes the "Yes" button grow bigger
6. After enough "No" clicks, only "Yes" is clickable
7. Clicking "Yes" shows "Perfect! I love you so much my forevermore ❤️"
8. Music switches to "Demolition Lovers"
9. Heart arrow button appears to continue to page 2

### Page 2 (love-letter.html):
1. Shows the romantic quote
2. Six song boxes displayed in a grid
3. Hovering over each box plays that song and shows the lyrics
4. Only one song plays at a time
5. Music stops when you move your mouse away

## Browser Compatibility

Works best in modern browsers:
- Chrome/Edge (recommended)
- Firefox
- Safari

**Note**: Some browsers block autoplay audio. Users may need to click on the page for music to start.

## Troubleshooting

**Music not playing:**
- The website uses YouTube embeds, so you need an internet connection
- Some browsers may block autoplay - click on the page to enable audio
- Make sure you're not using an ad blocker that blocks YouTube embeds

**Page looks broken:**
- Make sure you're viewing it through a web server (GitHub Pages, not just opening the file)
- Check browser console for errors
- Ensure you have an internet connection for YouTube API to load

**Songs not switching properly:**
- This is normal browser behavior with autoplay restrictions
- User may need to interact with the page first by clicking

## Credits

- Fonts: Google Fonts (Cinzel, Crimson Text)
- Design: Custom gothic romance theme
- Music: YouTube embedded players
- Songs by: HIM, My Chemical Romance, System of a Down, The Cure, London After Midnight, Deftones

## Song Lyrics Included

All lyrics are interpretations and kept brief to respect copyright:
- "Bury me deep inside your heart where I can never escape you."
- "We will be each other's ruins until the end of time."
- "It's my most lonely day, my eyes are dry but my soul aches."
- "I will give you all my love and never let it fade."
- "I live only to worship you, my sacrifice, my everything."
- "Drive far away, leave the world behind, just you and me."

## License

This is a personal project created with love for Jay.

---

Made with 🖤 for Jay
