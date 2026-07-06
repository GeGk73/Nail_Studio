[README.md](https://github.com/user-attachments/files/29690808/README.md)
# 💅 Nail Studio — Εικονικό Μανικιούρ / Virtual Manicure

[Ελληνικά](#ελληνικά) | [English](#english)

---

## Ελληνικά

Δοκίμασε βερνίκι νυχιών **ζωντανά** μέσα από την κάμερα του κινητού σου. Η εφαρμογή εντοπίζει τα δάχτυλά σου και "βάφει" τα νύχια σε πραγματικό χρόνο με το χρώμα και το εφέ που διαλέγεις.

### Χαρακτηριστικά

- 📷 Ζωντανή προβολή από την κάμερα (μπροστινή ή πίσω), ανίχνευση έως 2 χεριών
- 🎨 21 αποχρώσεις βερνικιών
- ✨ 4 εφέ: Απλό, Γαλλικό, Glitter, Ombre
- 💎 Φινίρισμα Γυαλιστερό ή Ματ, ρύθμιση μεγέθους νυχιού
- 📸 Λήψη screenshot — αποθηκεύεται ως εικόνα PNG
- 🖼️ Εναλλακτική με ανέβασμα φωτογραφίας χεριού, αν δεν υπάρχει κάμερα
- Ένα μόνο αρχείο HTML — χωρίς εγκατάσταση, χωρίς backend

### Τεχνολογία

- [MediaPipe Hands](https://developers.google.com/mediapipe) (Google) για την ανίχνευση των δαχτύλων — φορτώνεται από CDN
- HTML5 Canvas για τη σχεδίαση των νυχιών
- Καθαρή JavaScript, χωρίς frameworks

### ⚠️ Σημαντικό: απαιτείται HTTPS

Οι browsers επιτρέπουν πρόσβαση στην κάμερα **μόνο** μέσω HTTPS (ή localhost). Αν ανοίξεις το αρχείο απευθείας (`file://`), η κάμερα δεν θα λειτουργήσει — γι' αυτό ανέβασέ το σε δωρεάν hosting όπως παρακάτω.

### Ανέβασμα στο GitHub Pages (δωρεάν)

1. Σύνδεση/εγγραφή στο [github.com](https://github.com)
2. Πάτα **+** πάνω δεξιά → **New repository** → όνομα π.χ. `nail-studio` → **Public** → **Create repository**
3. Πάτα **uploading an existing file** και ανέβασε το αρχείο **μετονομασμένο σε `index.html`** → **Commit changes**
4. Πήγαινε **Settings → Pages** → Source: **Deploy from a branch** → Branch: `main`, φάκελος `/ (root)` → **Save**
5. Σε 1–2 λεπτά η εφαρμογή θα είναι διαθέσιμη στο:
   `https://TO_USERNAME_SOY.github.io/nail-studio/`

### Εναλλακτικά: Netlify Drop (πιο γρήγορο)

1. Μετονόμασε το αρχείο σε `index.html`
2. Πήγαινε στο [app.netlify.com/drop](https://app.netlify.com/drop)
3. Σύρε το αρχείο στη σελίδα — παίρνεις αμέσως link με HTTPS

### Χρήση

1. Άνοιξε το link από το κινητό σου
2. Πάτα **«Άνοιγμα κάμερας»** και δώσε άδεια πρόσβασης
3. Δείξε το χέρι σου με ανοιχτή παλάμη, σε καλό φωτισμό
4. Διάλεξε χρώμα, εφέ και φινίρισμα από το κάτω μενού
5. Πάτα το στρογγυλό κουμπί για screenshot

**Συμβουλές:** Καλός φωτισμός και απλό φόντο βελτιώνουν πολύ την ανίχνευση. Η τοποθέτηση του βερνικιού είναι προσεγγιστική — βασίζεται στις άκρες των δαχτύλων, όχι στο ακριβές περίγραμμα του νυχιού.

---

## English

Try on nail polish **live** through your phone's camera. The app detects your fingers and "paints" your nails in real time with the color and effect you choose.

### Features

- 📷 Live camera view (front or back), detects up to 2 hands
- 🎨 21 polish shades
- ✨ 4 effects: Plain, French, Glitter, Ombre
- 💎 Glossy or Matte finish, adjustable nail size
- 📸 Screenshot capture — saved as a PNG image
- 🖼️ Photo upload fallback if no camera is available
- Single HTML file — no installation, no backend

### Technology

- [MediaPipe Hands](https://developers.google.com/mediapipe) (Google) for finger detection — loaded from CDN
- HTML5 Canvas for nail rendering
- Vanilla JavaScript, no frameworks

### ⚠️ Important: HTTPS required

Browsers allow camera access **only** over HTTPS (or localhost). Opening the file directly (`file://`) will not work with the camera — deploy it to free hosting as described below.

### Deploy to GitHub Pages (free)

1. Sign in / sign up at [github.com](https://github.com)
2. Click **+** (top right) → **New repository** → name it e.g. `nail-studio` → **Public** → **Create repository**
3. Click **uploading an existing file** and upload the file **renamed to `index.html`** → **Commit changes**
4. Go to **Settings → Pages** → Source: **Deploy from a branch** → Branch: `main`, folder `/ (root)` → **Save**
5. In 1–2 minutes the app will be live at:
   `https://YOUR_USERNAME.github.io/nail-studio/`

### Alternative: Netlify Drop (fastest)

1. Rename the file to `index.html`
2. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
3. Drag and drop the file — you instantly get an HTTPS link

### Usage

1. Open the link on your phone
2. Tap **"Άνοιγμα κάμερας" (Open camera)** and grant camera permission
3. Show your hand with an open palm, in good lighting
4. Pick a color, effect and finish from the bottom panel
5. Tap the round button to take a screenshot

**Tips:** Good lighting and a plain background greatly improve detection. Polish placement is approximate — it's based on fingertip positions, not the exact nail outline.

---

### Άδεια / License

Ελεύθερο για προσωπική χρήση. Το MediaPipe διανέμεται υπό την άδεια Apache 2.0 της Google.
Free for personal use. MediaPipe is distributed under Google's Apache 2.0 license.
