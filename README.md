# Adder Explorer

An interactive walkthrough of how logic gates add binary numbers, from a half adder to a full adder to a 4-bit ripple-carry adder (OCR A Level Computer Science, H446).

## Features

### Tabs
- **Half adder** — click A and B to see the sum and carry, with the truth table and the expressions S = A ⊻ B and C = A ∧ B
- **Full adder** — the same with a carry in
- **4-bit adder** — add two 4-bit numbers one column at a time, or play the whole addition through
- **Practise** — add two numbers the way a ripple-carry adder would, with checking

### Teaching features
- Click a truth table row to set the inputs
- A plain-English explanation of each circuit
- Random numbers for the 4-bit adder

## How to Use

1. Open `index.html` in any modern browser (Chrome, Firefox, Edge, Safari). Nothing to install, no login.
2. Start on **Half adder** and toggle the inputs
3. Move to **Full adder**, then **4-bit adder** and press **Next bit**
4. Finish with **Practise**

## Use Cases

- Introducing adders before students build them
- A quick demonstration on the board
- Revision of half and full adders

## Tech

- A single HTML file: HTML, CSS and plain JavaScript
- No libraries, no build step, no backend
- Light and dark themes

---

## License

Copyright © Neil Southin. Free for personal use. Schools, colleges, and organisations wishing to use this in classrooms or on a VLE must get in touch first — see [LICENSE.md](LICENSE.md) for full details or email **southinn@colchsfc.ac.uk**.
