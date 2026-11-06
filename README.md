# 🎄 Sweet Paws Café

A cozy Christmas typing game. Cute chibi animal customers line up at a packed, decorated café counter.
Type the word in each customer's bubble to serve their dessert and earn cash and tips.

เกมฝึกพิมพ์ธีมร้านขนมคริสต์มาส: พิมพ์คำในบอลลูนของลูกค้าสัตว์ให้ครบเพื่อเสิร์ฟขนมและรับเงิน

## Play

- **Local:** open `index.html` in any modern browser (Chrome / Edge / Firefox). No install, no internet needed.
- **Online:** GitHub Pages (see below).

## How to play

- Start typing. The first letter picks the customer whose word starts with it.
- `Esc` switches to another customer, and `Backspace` starts the current word over.
- Serve fast for bigger tips. Serve without typos to build a 🔥 combo.
- A customer who waits too long leaves grumpy, and you lose a ❤️.
- ⚙️ Settings, ↺ Restart and ⛶ Full screen work at any time.

### Settings

| Difficulty | |
|---|---|
| 🍼 Easy | patient customers, 5 ❤️ |
| ☕ Normal | the default |
| 🔥 Hard | impatient customers, longer words sooner |

Word sets: 🧁 Desserts · 📖 Everyday words · 📚 Long vocabulary (10–17 letters) · 🎲 Mix all

### Stats

- Live accuracy is shown in the top bar.
- WPM, accuracy, served and mistakes appear at the end of each day.
- High scores (per difficulty) and best WPM are saved in your browser (localStorage).

## Tech

- A single `index.html` file in plain HTML, CSS and JavaScript, with no libraries or build step.
- The café is a real 3D scene built with CSS 3D transforms.
- Characters and props are inline SVG, and some props are emoji.
- Sound effects are generated with the Web Audio API, so there are no audio files.
