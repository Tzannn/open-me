# 💕 Will You Go On A Date With Me?

A cute little pink web app to ask your girlfriend out. No installation needed.

## ▶️ How to open it
Just **double-click `index.html`** — it opens in any web browser (phone or computer).
To send it to her, you can host it for free on Netlify Drop, GitHub Pages, or just open it on your own device together.

## ✏️ How to change the words
Open **`index.html`** in any text editor (Notepad works) and scroll down to the part that says:

```
const CONFIG = {
```

Everything you can change is right there — every heading, button, food item, and message.
Just edit the text inside the quotes `"like this"` and save the file. That's it!

What you can change:
1. **Step 1** – the "Will you go on a date with me?" question, the Yes/No text, and the celebration line.
2. **Step 2** – the date & time headings and descriptions (and the default time).
3. **Step 3** – the "What are we feeling?" foods. Add, remove, or rename any item — each looks like `{ name: "Pizza", emoji: "🍕" }`.
4. **Step 4** – the summary headings and the final message.

## 📷 How to add your photo
There's one photo spot — it shows right after she taps **YES** 🥰
1. Put your image file (e.g. `us.jpg`) into the **`photos`** folder next to this file.
2. In `index.html`, find the `photos:` section near the top of CONFIG and set the name:

```js
photos: {
  celebrate: "photos/us.jpg",   // shown right after she says YES
},
```

Leave it as `""` (empty) to show a friendly “Add a photo here” placeholder instead.

## 🎨 How to change the colours
At the very top of the `<style>` section in `index.html` you'll see `:root { --pink-deep: ... }`.
Change those colour codes to recolour the whole app.

## ✨ Features
- The **No** button runs away from the cursor (and from taps on mobile) — and each time it dodges, the **Yes** button grows bigger and bigger until it almost fills the screen. Only Yes can be clicked!
- Falling-hearts celebration when she says yes.
- A pink calendar to pick the date + a time picker.
- Multi-select food picker (9 choices — easy to add more).
- A final summary with a **“Copy to send 💌”** button so she can paste the plan straight into your chat.

## 📋 The “Copy to send” button
On the summary page she taps **Copy to send** and the whole plan (date, time, food) is copied as text, ready to paste into your chat. If her browser ever blocks auto-copy, a little box pops up with the text already selected so she can copy it by hand.

Have fun! 💖
