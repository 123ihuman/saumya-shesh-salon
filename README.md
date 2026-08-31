# सौम्या एंड शेष हेयर सैलून — Website

यह एक तैयार (ready-to-upload) वेबसाइट है — plain HTML/CSS/JS में बनी है, कोई build step नहीं चाहिए।

## GitHub पर अपलोड करने का तरीका (Step-by-Step)

### तरीका 1 — GitHub वेबसाइट से सीधे अपलोड (सबसे आसान, बिना कोड के)

1. https://github.com पर जाकर account बनाएं / लॉगिन करें
2. ऊपर दाईं तरफ **+** आइकन → **New repository** पर क्लिक करें
3. Repository का नाम दें, जैसे: `saumya-shesh-salon`
4. **Public** चुनें (GitHub Pages फ्री में सिर्फ Public repo पर काम करता है, जब तक आपका Pro/Team plan न हो)
5. **Create repository** दबाएं
6. अगली स्क्रीन पर **"uploading an existing file"** लिंक पर क्लिक करें
7. इस folder के अंदर की **सभी चीज़ें** (`index.html`, `images` folder, `videos` folder, `.nojekyll`) एक साथ drag-and-drop करें
   - ध्यान रखें: folder structure वैसी ही रहनी चाहिए — `images/` और `videos/` root में `index.html` के साथ ही होने चाहिए
8. नीचे **Commit changes** दबाएं (upload होने में वीडियो की वजह से थोड़ा समय लगेगा — 23MB डेटा है)

### GitHub Pages चालू करें (वेबसाइट लाइव करने के लिए)

1. Repository के अंदर ऊपर **Settings** टैब पर जाएं
2. बाईं तरफ मेनू में **Pages** पर क्लिक करें
3. **Build and deployment** के नीचे **Source** में चुनें: `Deploy from a branch`
4. **Branch** में चुनें: `main` और folder में चुनें: `/ (root)`
5. **Save** दबाएं
6. 1-2 मिनट रुकें, फिर पेज को reload करें — ऊपर हरे रंग में एक लिंक दिखेगी जैसे:
   `https://yourusername.github.io/saumya-shesh-salon/`
7. यही आपकी लाइव वेबसाइट की लिंक है — इसे किसी को भी भेज सकते हैं

### तरीका 2 — Git कमांड से (अगर Git इस्तेमाल करना आता है)

```bash
cd path/to/this/folder
git init
git add .
git commit -m "Salon website first upload"
git branch -M main
git remote add origin https://github.com/yourusername/saumya-shesh-salon.git
git push -u origin main
```

फिर ऊपर बताए अनुसार Settings → Pages में जाकर चालू करें।

## जरूरी बातें (Important Notes)

- **Folder structure मत बदलें** — `index.html`, `images/`, `videos/` हमेशा एक साथ, एक ही स्तर (root) पर रहने चाहिए
- वीडियो फाइलें साइज़ में बड़ी हैं (कुल ~22MB) — इसलिए upload/commit होने में कुछ मिनट लग सकते हैं, धैर्य रखें
- वेबसाइट लाइव होने में GitHub Pages को कभी-कभी 2-5 मिनट लग जाते हैं, पहली बार में तुरंत न दिखे तो थोड़ा रुककर दोबारा देखें
- बुकिंग फॉर्म सबमिट होने पर WhatsApp नंबर 9369224174 पर सीधे संदेश जाता है — यह पहले से सेट है, कुछ बदलने की जरूरत नहीं
