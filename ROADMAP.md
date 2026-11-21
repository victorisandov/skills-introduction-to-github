# Weather Color Picker: Roadmap

Goal: a fun browser app that suggests what color to wear for the temperature.
Cold weather gets cooler colors. Warm weather gets warmer colors.
Built with plain HTML, CSS, and JavaScript. Temperatures are in °F.

Every milestone ends with something you can open in a browser and test.

## Milestone 1: It works (smallest version)
Open `index.html`, type a temperature, and get a color name and a message.

- [x] `index.html` with a temperature input and a "Pick my color" button
- [x] `script.js` maps the temperature to a color name and a message
- [x] Result shows the color name and the message
- [x] Friendly error if the input is empty or not a number

**Test:** open `index.html`, try 20, 45, 60, 75, 95, then try leaving it blank.

## Milestone 2: Weather emoji
The result also shows an emoji that matches the weather.

- [ ] Emoji for each temperature range (for example ❄️ 🧥 🌤️ ☀️ 🔥)
- [ ] Emoji appears large next to the color name
- [ ] Emoji updates every time a new temperature is entered

**Test:** try a very cold, mild, and very hot temperature and check the emoji changes.

## Milestone 3: Make it fun
The page looks and feels playful.

- [ ] Show a color swatch and change the page background to the suggested color
- [ ] Several messages per range, picked at random, so it stays fresh
- [ ] Playful styling: fonts, spacing, and a small animation when the result appears
- [ ] Looks good on a phone-sized window

**Test:** enter the same temperature a few times and see different messages. Resize the window.

## Milestone 4: Extras (optional)
Pick whichever of these you want after the first three.

- [ ] °F / °C toggle
- [ ] "Surprise me" button with a random temperature
- [ ] Matching palette of 3 to 5 colors
- [ ] Live weather lookup by city
