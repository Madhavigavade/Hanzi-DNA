# Manda | Hanzi DNA

See how Chinese characters are built. Type a hanzi (or pinyin, or an English word) and watch its memory picture turn into the modern strokes, part by part.

- 258 HSK 1–3 hanzi in 12 themed practice packs (Nature, Body, Family, Numbers, Time, Food, Home, School, Travel, Actions, Feelings, Directions)
- Memory picture for every part of every pack hanzi, then the real stroke order
- Pinyin, tone, meaning, radical, stroke count, an example word and sentence
- Audio for every pack hanzi, word and sentence (checked by two speech recognisers)
- History add-on: real oracle-bone glyphs where a reliable one exists
- Family trees: other characters built from the same parts

Everything is in one file (`index.html`). No server, no API key, no build step.

## Put it on GitHub Pages

1. Create a new public repository (for example `manda-hanzi-dna`).
2. Upload `index.html` (and this `README.md`) to the root of the repository.
3. Go to **Settings → Pages**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, and save.
4. After a minute the site is live at `https://<your-username>.github.io/manda-hanzi-dna/`.

Notes:
- The file is about 7.5 MB because the audio is built in; GitHub accepts files up to 100 MB.
- The only thing loaded from the internet is the Google Fonts stylesheet. Without a connection the page still works with system fonts.
- The "More examples from Claude" section only appears when the page runs inside claude.ai. On GitHub it is simply hidden.
- A character outside the packs has no built-in audio; it uses the device's Chinese voice if one is installed. A character with more than one reading stays silent rather than risk the wrong reading.

## Credits and licences

- Stroke data and decomposition: [Make Me a Hanzi](https://github.com/skishore/makemeahanzi) (Arphic Public License / LGPL)
- HSK levels and frequency: hanziDB
- Oracle-bone glyphs: oracle-bone-jgw-1203 dataset (npj Heritage Science, 2026), CC BY 4.0
- Voice: [Kokoro-82M](https://huggingface.co/hexgrad/Kokoro-82M) (Apache 2.0), voices zf_xiaoxiao, zf_xiaoyi, zf_xiaobei, zf_xiaoni; pinyin set by hand for every clip
- Fonts: Noto Sans SC and others via Google Fonts (SIL Open Font License)

Memory pictures are learning aids, not historical forms. The History add-on shows the attested oracle-bone glyphs.
