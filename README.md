# 🎉 Happy Father’s Day!

A heartfelt tribute to my amazing father — the one who taught me how to code.

This project is adapted from [ayusharma/birthday](https://github.com/ayusharma/birthday.git), with customizations to celebrate Father’s Day.

---

## 📦 Project Setup (Python)

1. Clone the project:

   ```bash
   git clone https://github.com/ayusharma/birthday.git
   cd birthday
   ```

2. Start a local server using Python 3:

  ```bash
  python -m http.server 8081
  ```

3. Open your browser and visit:
   
  ```arduino
  http://localhost:8081
  ```

## ✏️ Customization Guide

### 🎈 Change the Balloon Letters

After clicking the "Wish Message" button, balloons will float up with letters.

To change the letters, open the index.html file

Look for a line like:

  ```html
  <div class="balloons text-center" id="b1">
    	<h2 style="color:#F2B300;">H</h2>
  ```

Replace the letters with your own (e.g. initials)

### 💬 Change the Message Text

You can customize the lines of the message that appear after the balloons rise.

Open index.html

Scroll to the part labeled as the message section

Replace the sample lines with your own Father’s Day messages

### 🎵 Change the Background Music
The current background song is a Cantonese track:

《报答一生》 by BEYOND, a legendary Hong Kong band.

To use your own music, replace the existing .mp3 file in the project folder

Keep the filename the same (or update the path in index.html if you rename it)


## 💖 Why This Project?
Because coding is more than just a skill.

It’s love passed down through generations.

It’s about who stood by us when we started.

It’s about saying:

Thank you, Dad.

Happy Father’s Day 💙
