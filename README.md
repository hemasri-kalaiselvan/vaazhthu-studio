# Vaazhthu Studio

> A browser-based Tamil wish video maker that turns a name, a photo and a message into a 15-second animated video for birthdays, anniversaries and Indian festivals.

**Tech:** HTML5 Canvas, JavaScript, CSS, Web Audio API, MediaRecorder API
**Tools:** GitHub, GitHub Pages
**AI Tools:** Claude

## About

Vaazhthu Studio (வாழ்த்து வீடியோ) makes 15-second Tamil wish videos for birthdays, wedding anniversaries and Indian festivals, right in your phone's browser.

Enter a name, add a photo, type a wish in Tamil, English or both, and pick one of **133 animated templates**. The app records a WhatsApp-status-size video (720×1280, 9:16) with music, ready to download or share.

There is no server, no sign-up and no paid service. The whole app is one `index.html` file.

---

## Features

- **133 templates** in ten different looks:

  | Group | Count | Examples |
  |---|---|---|
  | Birthday (traditional) | 12 | Marigold Silk, Kolam Night, Temple Bells, Lotus Pond, Kanchi Pink |
  | Modern (birthday and anniversary) | 24 | Neon Glow, Glass Card, Cake and Candles, Heart Bokeh, Love Neon |
  | Kids | 12 | Rainbow Clouds, Jungle Friends, Under the Sea, Space Explorer |
  | Anniversary (traditional) | 8 | Jasmine Arch, Wedding Gold, Rose Petal Shower, Lotus Love |
  | Nature | 10 | Evergreen Hills, Misty Mountains, Coconut Coast, Snowy Pines |
  | Festivals | 34 | Pongal Paanai, Deepavali Crackers, Golu Steps, Crescent Moon, Pookalam |
  | Full photo (head to toe) | 14 | Royal Portrait, Temple Arch Portrait, Wedding Arch Portrait, Neon Portrait, Deepavali Family Portrait |
  | Party specials | 10 | Candle Letter Cake, Rose Balloon Sky, Golden Light Heart, Royal Crest, Marquee Night, Heart Rain |
  | Dancing cartoon | 9 | Disco Party Dance, Kuthu Dance Birthday, Veshti Celebration, Pavadai Princess, Super Hero Kid, Saree Celebration |

- **18 occasions**, each with its own Tamil and English title and ready-made wishes: Birthday, Wedding anniversary, Pongal, Deepavali, Karthigai Deepam, Tamil New Year, New Year, Vinayagar Chathurthi, Navaratri, Ayudha Pooja, Krishna Jayanthi, Christmas, Ramzan / Eid, Onam, Holi, Raksha Bandhan, Independence Day and Republic Day.
- **Animated effects:**
  - balloons, confetti, streamers and bubbles
  - blooming flowers and lotus
  - glowing stars, fireworks, flowerpot crackers and sparklers
  - rainbows, clouds, sun and moon
  - hills, pine forests, palm trees and waves
  - walking elephants, deer and rabbits, plus butterflies, birds and fish
  - diyas, lanterns, kolam and rangoli, zari borders and mango-leaf thoranam
  - a boiling Pongal pot, sugarcane, golu steps, modak, a snake boat and Christmas trees
- **Long wishes and poems:** up to 800 characters with line breaks kept. A long wish opens in its own card after the intro, line by line, and the video grows from 15 seconds up to 40 seconds so every line can be read.
- **Photo adjust:** drag the photo in the preview to position the face, pinch or use the slider to zoom, or use the arrow buttons.
- **Age badge:** enter an age or number of years (for example 60) to get a gold "60" medallion and titles like "இனிய 60ஆம் பிறந்தநாள்" and "Happy 60th Birthday".
- **Animated title:** each word pops in, then a shine sweeps across, with glowing sparkles and a decorative underline.
- **Photo frames:** circle, temple arch, heart, hexagon, polaroid, tall portrait and tall temple arch.
- **Photo shape for any template:** Template, Full photo (head to toe), Circle or Square. **Fit whole photo** zooms out so nothing is cut off, filling the sides with a soft blur.
- **Rich effects:** a gold sparkle burst when the photo appears, a glossy shine across the frame, ornate gold frames, corner flowers and moving light flares.
- **Nine looks** so templates don't look alike: Classic, Full-screen photo, Ribbon banner, Big name poster, Temple doors (opening wooden doors), Stage curtains, Film strip, Neon sign and Full photo. Filter by look with the **Look** menu.
- **Dancing cartoon (3D):** the face from your photo goes on an original lit 3D cartoon body (Three.js), which turns and twists as it dances; a 2D version is used if 3D can't load or is switched off that dances (kuthu, bhangra, disco, twist, jump, wave and superhero moves) in outfits such as veshti, kurta, pavadai, saree, party wear, a disco suit and a superhero suit. Hands and neck match the face colour automatically (or pick a colour), and pick **Dancing cartoon** under Photo shape to use it with any template.
- **Changing backgrounds:** an option that cross-fades three matching scenes behind the same photo and text.
- **Caption-style wishes:** an option that shows the wish two lines at a time in bold, colourful outlined text, like song lyrics.
- **Party effects:** a glowing heart of light, a light ring with sparkles, a ring of stars, rainbow candle letters, a hot-air balloon made of roses with a scroll banner, a royal crown-and-wings crest, a light-bulb marquee sign, neon light streaks and big petals falling in the foreground.
- **Cinematic effects (on by default, can be switched off):** fade-in from dark, slow camera zoom, rotating light rays behind the photo, two lights orbiting the frame, a flash when the photo appears, a 3D glitter name and a golden sparkle shower at the end.
- **Clean music:** each tune is prepared once in the background and played as a single audio track, so it doesn't crackle while the animation runs.
- **Five Tamil font styles:** Arima, Catamaran, Baloo Thambi 2, Coiny and Kavivanar (all from Google Fonts).
- **Title language:** Tamil, English or both.
- **19 built-in tunes**, each with a **▶ Listen** button so you can hear it before choosing:

  | Group | Tunes |
  |---|---|
  | Birthday | Birthday bells, Piano birthday waltz, Happy ukulele, Celebration fanfare |
  | Tamil and Indian | Nadaswaram melam, Veena Mohanam, Bansuri flute, Temple morning, Parai kuthu, Sitar festive |
  | Love and soft | Mangala arpeggio, Strings of love, Harp dream, Lo-fi chill |
  | Kids | Twinkle music box |
  | Modern | Modern pop beat, Party EDM |
  | Festival songs | Jingle Bells, Auld Lang Syne |

  You can also use your own audio file, with an optional start and end time in separate minute and second boxes (for example 0 min 45 sec to 1 min 5 sec), or no music. If the chosen part is shorter than the video, it repeats. Each template picks a fitting tune by default, such as parai for Pongal, sitar for Deepavali and Jingle Bells for Christmas.
- **Search and filter:** category chips plus a search box, so typing "pongal", "neon" or "balloons" finds matching templates.
- **Remembers your inputs** in the browser, so the name, wish and chosen template are still there next time.

---

## How to use

1. Open the app in **Chrome** on your phone or computer.
2. **Template:** tap a category chip or search, then pick a design.
3. **Occasion:** this is set automatically by the template, and you can change it from the dropdown. Choose the title language.
4. **Photo and names:** choose a photo and drag it in the preview to position the face, then tap **Done**. Type the name, an optional "From" line and an optional age.
5. **Wish message:** type your own wish, or tap a ready-made one (தமிழ், English or Both).
6. **Music:** tap **▶ Listen** on any tune to hear it first, then select the one you like. You can also use your own audio file or no music.
7. Tap **Play with music** to preview.
8. Tap **Create video**. Keep the screen on and the app open while it records (15 seconds, or longer for a long wish).
9. Tap **Download video** or **Share** to send it on WhatsApp.

---

## Publish on GitHub Pages

1. Create a new repository on GitHub, for example `vaazhthu-studio`.
2. Upload `index.html` and this `README.md` to the repository's main branch.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to *Deploy from a branch*. Choose `main` and `/ (root)`, then click **Save**.
5. After a minute or two, the app is live at `https://<your-username>.github.io/vaazhthu-studio/`.

To update the app later, upload the new `index.html` over the old one. GitHub Pages refreshes automatically.

---

## How it works

| Part | Technology |
|---|---|
| Drawing the animation | HTML5 Canvas 2D, 720×1280 at 30 fps |
| 3D dancers | Three.js 0.149 (WebGL), loaded from jsDelivr |
| Recording the video | `canvas.captureStream()` and `MediaRecorder` |
| Music | Web Audio API: tunes are synthesised live, and your own file is decoded and mixed in |
| Tamil text | Google Fonts with Tamil support, wrapped and sized to fit automatically |
| Sharing | Web Share API (where the phone supports it) |
| Storage | `localStorage` for your last inputs; photos and audio never leave your device |

Every frame is calculated from the time alone, so the preview, the thumbnails and the recorded video always match.

### Video format

- **MP4** on recent Chrome (Android and desktop). It plays in WhatsApp, Instagram and the phone gallery.
- **WebM** on browsers that can't record MP4. It plays in Chrome and YouTube, but WhatsApp may not accept it.

---

## Adding your own template

Templates are one line each, in the `/* ---------- 100 templates ---------- */` section of `index.html`:

```js
T('Template Name', 'Category', 'occasion',
  ['l', '#topColour', '#bottomColour'],   // background: 'l' linear, 'r' radial, 'b' moving blobs
  'gold',                                 // text palette: gold, night, rose, teal, kids, pastel, neon, luxe, …
  ['stars', ['balloons', {n: 6}], 'garland'],  // effects, with optional settings
  {fr: 'heart', f: 'script', L: 'base', mod: true}  // frame, font style, layout, modern tag
);
```

- **Categories:** `Birthday`, `Kids`, `Anniversary`, `Nature`, `Festival`
- **Frames (`fr`):** `circle`, `arch`, `heart`, `hex`, `polaroid`
- **Fonts (`f`):** `classic`, `modern`, `kids`, `fun`, `script`
- **Layouts (`L`):**
  - `classic`: photo in the centre
  - `base`: leaves room at the bottom for a cake, pot, golu or similar
  - `top`: large photo at the top
- **Effects:** every name in the effects library section, such as `balloons`, `bloom`, `fireworks`, `rainbow`, `hills`, `animals`, `diyas`, `lanterns`, `pongalPot`, `cake`, `snow` and `holi`

---

## Music and copyright

The built-in tunes are generated live in the browser. They are original compositions or public-domain melodies (Happy Birthday, Twinkle Twinkle Little Star, Jingle Bells and Auld Lang Syne), so videos made with them are safe to share.

Film songs and other commercial music are copyrighted. The app does not include any. If you add a song with **My own audio**, use it only for personal sharing, or use music you have the rights to.

---

## Browser support

| Browser | Status |
|---|---|
| Chrome on Android | Best experience; records MP4 |
| Chrome / Edge on desktop | Works fully |
| Firefox | Works; records WebM |
| Safari on iPhone | Preview works; recording support depends on the iOS version |

Recording happens in real time, so a 15-second video takes about 15 seconds. Keep the screen on and the tab in front while it records.

---

## Roadmap

- Drag and zoom to position the face inside the frame
- Convert WebM videos to MP4 for WhatsApp on older phones
- Square (1:1) size for Instagram posts
- More templates: wedding invitations, baby's first birthday, retirement and house-warming
- Wrap as an Android app for the Play Store

---

## Author

Built by **Hemasri Kalaiselvan** as part of a hands-on AI and web learning portfolio.
