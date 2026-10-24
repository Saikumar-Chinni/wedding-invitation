# Venkata Saikumar ♥ Rohini Varalakshmi — Royal Wedding Celebrations

A mobile-first, high-end digital wedding invitation website crafted in the **Royal Emerald Green & 24K Gold Foil** style inspired by **InviteStory (@invitestory.in)**, built with pure HTML5, CSS3, and modern JavaScript.

---

## Auspicious Celebrations & Event Schedule

### 1. Haldi & Sangeeth Celebrations (పసుపు వేడుక & సంగీత్ నైట్)
- **Auspicious Date:** Thursday, 19 November 2026
- **Haldi Ceremony (మంగళ స్నానం & పసుపు):** Morning Celebration
- **Sangeeth & Musical Night (సంగీత్):** Evening / Night Celebration
- **Sacred Venue:** **Ambica Sea Green**, Beach Road, Visakhapatnam, Andhra Pradesh
- **Google Maps:** [https://maps.app.goo.gl/HKqPGgwte3YvETWB6](https://maps.app.goo.gl/HKqPGgwte3YvETWB6)
- **Attire:** Haldi: Festive Yellow / Gold · Sangeeth: Glamorous Indian

### 2. Subha Vivaham (The Sacred Wedding Ceremony · కల్యాణ మహోత్సవం)
- **Auspicious Date:** Friday, 20 November 2026
- **Subha Muhurtham:** **9:53 PM** (Night · Karthika Masam · Sukla Paksham · జీలకర్ర బెల్లం)
- **Sacred Venue:** **TTD Kalyana Mandapam**, MVP Colony, Visakhapatnam, Andhra Pradesh
- **Google Maps:** [TTD Kalyana Mandapam on Google Maps](https://www.google.com/maps/search/?api=1&query=TTD+Kalyana+Mandapam+MVP+Colony+Visakhapatnam)
- **Attire:** Traditional Silk / Festive Attire (Pattu Sarees, Kurta & Dhoti)

### 3. Sri Satyanarayana Swamy Vratham & Festive Wedding Lunch (వ్రతం & కల్యాణ విందు)
- **Auspicious Date:** Sunday, 22 November 2026
- **Morning Pooja:** Auspicious Sri Satyanarayana Swamy Vratham, Katha Shravanam, & Mahamangala Harathi
- **Festive Wedding Lunch (కల్యాణ విందు భోజనం):** Sumptuous traditional Andhra feast served on fresh banana leaves (అరటి ఆకు భోజనం) with Godavari specialties and divine Satyanarayana Swamy Mahaprasadam
- **Sacred Venue:** **Sri Sai Krishna Mandir**, 2-60-5, Sambhu Nagar, Alcot Gardens, Rajamahendravaram (Rajahmundry), Andhra Pradesh 533101
- **Google Maps:** [https://maps.app.goo.gl/oMhQ2octoprPrzRn9](https://maps.app.goo.gl/oMhQ2octoprPrzRn9)

---

## Key Features & Cultural Elements

1. **Royal Emerald & Gold Foil Wax Seal Screen:**
   - Features the royal emerald green raw silk aesthetic with golden mandala tracing, the embossed **"RS" Wax Seal**, and **"TAP THE SEAL TO OPEN"** prompt.
   - Unlocks the invitation with a sacred temple bell chime, soothing Raag Mohanam flute/tanpura melody, and a celebratory burst of sacred Akshatas and rose petals.

2. **Real Couple Photograph in Royal Golden Jharokha Arch:**
   - Features the real photograph of bride Rohini Varalakshmi and groom Venkata Saikumar (`couple.jpg`) framed in an ornate golden temple arch with royal filigree borders.

3. **Floating Sticky Bottom Dock:**
   - 📅 **Save Date:** Multi-event calendar (.ics) download for Apple, Google, and Outlook calendars (All events, or individually).
   - 📍 **Directions:** Modal with direct navigation to all 3 celebration venues.
   - 🌸 **Bless:** Cascading physics burst of golden consecrated Akshatalu (rice grains) and rose petals.
   - 🎵 **Music:** Auspicious classical Tanpura drone and Raag Mohanam flute synthesizer with animated soundwave indicator.

4. **Live Muhurtham Countdown Clock:**
   - Real-time countdown tracking days, hours, minutes, and seconds until the sacred Muhurtham at 9:53 PM on 20 November 2026.

5. **Telugu Vivaha Veduka Traditions Guide:**
   - Highlights the 4 sacred rites: *Mangala Snanam & Pasupu*, *Gauri Pooja & Kanyadaanam*, *Jeelakarra Bellam (Sumuhurtham)*, and *Mangalyadharana & Saptapadi*.

6. **Interactive Aashirwadam (Blessings Wall):**
   - Guests can bestow their wishes and blessings, select their relationship (Family Elders, Friends, Well-wishers), and receive an instant floral burst. Blessings persist across sessions using `localStorage`.

---

## Local Development & Preview

Run a local HTTP server:
```bash
python3 -m http.server 8000
```
Then open `http://localhost:8000` in your browser.

---

## How to Change the Background Music

You have two easy ways to set your favorite wedding track:

### Option 1: Drop your MP3 file (Easiest)
1. Copy any MP3 song (e.g. your favorite Nadaswaram, Shehnai, or wedding song) into the project folder.
2. Name the file `music.mp3`.
3. That's it! When guests open the seal or tap the Music button, your MP3 song will automatically play.

### Option 2: Use an Online Audio URL or Different File Name
1. Open `index.html`.
2. Find line 24:
   ```html
   <audio id="weddingAudio" src="music.mp3" preload="auto" loop></audio>
   ```
3. Change `src="music.mp3"` to your file's name (e.g. `src="my_song.mp3"`) or a web URL (e.g. `src="https://example.com/wedding_song.mp3"`).

*Note: If no MP3 file is present, the website automatically falls back to the built-in serene Indian classical Tanpura drone and Raag Mohanam flute synthesizer, so music will always play seamlessly!*

---

## Deployment to GitHub Pages

1. Push or upload `index.html`, `style.css`, `script.js`, `couple.jpg`, `music.mp3` (if you added one), and `README.md` to your GitHub repository root.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select branch `main` and folder `/(root)`, then click **Save**.
4. Your live royal wedding invitation will be live and shareable!
# wedding-invitation
