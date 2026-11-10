# 🎄 Christmas Wonderland — A Magical Christmas Experience 🎄

An award-winning, interactive digital Christmas greeting website built with modern web technologies, Three.js 3D graphics, Web Audio API procedural music synthesis, GSAP, and Tailwind CSS.

---

## 🌟 Key Features Included

1. **Cinematic Introduction (Hero)**
   - Starry night sky with dynamic 2D snowfall canvas physics.
   - Aurora borealis atmospheric gradients and ambient glowing ornaments.
   - Cinematic Merry Christmas typography (Cinzel & Playfair Display).
   - "Enter The Christmas Experience" button that smoothly transitions to the 3D world and starts carols.

2. **Interactive 3D Christmas World (Three.js)**
   - Fully textured 3D pine Christmas tree with conical branches and bark trunk.
   - 100+ shiny reflective baubles in ruby, gold, emerald, and sapphire.
   - Dynamic helical fairy lights twinkling with harmonic sine waves.
   - 3D rotating Golden Star of Bethlehem topper with point light illumination.
   - Snow-covered terrain with soft undulating hills.
   - Cozy log cabins with snow roofs and warm glowing amber windows.
   - Flying 3D Santa's Sleigh and 4 Reindeer soaring across the sky on a celestial flight path!
   - Ethereal Northern Lights (Aurora Borealis) waving across the horizon.
   - 2,000+ 3D falling snow particles.
   - Interactive camera orbit, mouse drag, touch gestures, zoom, and preset viewpoint buttons ("Tree Focus", "Village View", "Sky & Sleigh", "Auto-Rotate").
   - Atmosphere switcher ("Midnight Frost", "Northern Aurora", "Sunset Amber").

3. **Grand Christmas Greeting Experience**
   - Monumental animated "MERRY CHRISTMAS!" heading in shimmering gold gradient.
   - Heartfelt blessing: *"May this Christmas fill your heart with happiness, your home with warmth, and your life with endless blessings. Wishing you and your loved ones a season filled with love, laughter, peace, and unforgettable memories."*
   - Interactive Cathedral Blessing Chime button.

4. **Personalized Christmas Greetings Studio**
   - Recipient and Sender name inputs.
   - 4 ornate visual themes (Royal Emerald, Fireside Velvet, Northern Aurora, Midnight Gold).
   - Greeting message presets & custom message support.
   - Live interactive 3D-tilting card preview with real-time updates.
   - Instant WhatsApp sharing (`https://api.whatsapp.com/send?text=...`).
   - Copy formatted greeting text with toast notification.
   - Shareable card URL parameter support (`#to=Name&from=Sender`).
   - High-resolution card download as PNG rendered via offscreen canvas.

5. **Live Christmas Countdown**
   - Precise live countdown to December 25, 2026.
   - Days, Hours, Minutes, and Seconds flip/glass tiles.
   - Automatic transition to celebratory fireworks banner on Christmas Day.

6. **Interactive 3D Gift Box**
   - 3D isometric gift box with ribbon and satin bow.
   - Hover rumble and anticipation wobble.
   - Click/tap: ribbon unties, lid flies open, golden light beam shoots up, confetti explosion bursts, and a heartfelt gift blessing scroll is revealed!
   - Ability to unwrap multiple unique gift blessings.

7. **Christmas Music Experience & Visualizer**
   - 100% royalty-free procedural synthesizer built on Web Audio API (never fails or 404s).
   - Celesta, carillon bells, and warm harmonic pad timbres.
   - 4 Christmas classics: "We Wish You a Merry Christmas", "Jingle Bells", "Silent Night", "Deck the Halls".
   - Real-time 20-band audio frequency visualizer with golden equalizer bars.
   - Full playback controls: Play/Pause, Next/Prev, Volume slider, Mute toggle.
   - Autoplay safe (starts strictly upon user interaction).

8. **Christmas Memory Wall & Gallery**
   - 6 nostalgic holiday memory Polaroid cards with illustrated scenes and stories.
   - Fullscreen Lightbox viewer for any photo card.
   - Local photo upload feature: upload real photos from your computer, give them titles and captions, and pin them directly to the wall with confetti!

9. **Secret Christmas Surprise**
   - Mysterious glowing button: *"A LITTLE CHRISTMAS SURPRISE"*.
   - Fullscreen celestial modal with starry particles, emotional holiday letter, and an interactive "Make a Christmas Wish" feature that releases an animated lantern into the sky.

10. **Magical Effects & Polish**
    - Parallax 2D falling snowflakes canvas.
    - Golden fairy dust mouse trail particles on desktop.
    - Custom gold ring cursor.
    - Retro glowing holiday light bulb string.
    - Responsive mobile navigation drawer.
    - Fullscreen toggle button.
    - Respects reduced-motion accessibility settings.

---

## 🌐 Publish and share with GitHub Pages

The `127.0.0.1` address from a local preview only works on your own computer. To give family a link they can open:

1. Create a GitHub repository for this site. For GitHub Free, make it **public**.
2. Upload `index.html`, this `README.md`, and the `.github/workflows/pages.yml` file to the repository's `main` branch. Keep the workflow at that exact path.
3. In the repository, open **Settings → Pages** and set the build and deployment source to **GitHub Actions**.
4. Open the **Actions** tab and wait for the **Deploy to GitHub Pages** workflow to finish successfully.
5. In **Settings → Pages**, copy the published URL. It will look like `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`. Send that URL to your family.

The workflow republishes the site whenever you push a change to `main`. Personalized card links use the published page URL automatically.

## 🛠️ Preview locally in VS Code

Open the folder containing `index.html` in VS Code and use the Live Server extension, or open `index.html` directly in a browser. A local address such as `http://127.0.0.1:5500/` is only for your own device and cannot be shared.

Click **"ENTER THE CHRISTMAS EXPERIENCE"** to start the music and explore the magical 3D world!

---
*Made with love. Shared with everyone. Merry Christmas 2026!*
