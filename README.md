# 🪩 Retro-Cyberpank Portfolio

A retro-cyberpunk themed portfolio website with interactive effects and multilingual support. Built with pure HTML, CSS, and JavaScript (no frameworks required!).
```
🕶 Warning:
May cause sudden urges to play retro arcade games or start hacking (ethically, of course)
```
You can see my personal website here -> https://klivvi.github.io/
And template website here -> https://klivvi.github.io/template/
## 🔮 What's This?

This is my personal portfolio website with a cool retro aesthetic. Think Matrix meets old-school video games. I built it to showcase my projects and achievements while having some fun with animations and effects.

The best part? I'm also sharing a template version so you can make your own cyberpunk portfolio without starting from scratch!

## 🔱 Cool Features

**Visual Effects**
- **Matrix Rain Animation** - Falling characters in the background (yes, just like *that* movie)
- **Customizable Mouse Trail** - Your cursor leaves glowing particles as you move
- **Glow Effects** - Text that lights up on hover because why not
- **Full Theme Customization** - Change colors, background, accent colors on the fly

**Language Support**
- Switch between English, Russian, and Korean
- Even changes the font style to match the language!

**Interactive UI**
- Side navigation panel that slides in/out
- Project cards with modal popups for details
- News/blog section
- Settings panel to customize everything

## 📁 Repository Structure

```
main branch (my personal site)
├── index.html          # My portfolio with personal info
├── src/                # Images and assets
└── template            # Folder for template website (so you can see it online as an actual website)

template branch (for you!)
├── template.html       # Clean version ready to customize
└── src/                # Placeholder images
```

## 🔅 How to Use the Template

1. **Get the template**
   ```bash
   git clone -b template https://github.com/klivvi/klivvi.github.io.git template-folder
   ```

2. **Customize your content**
   - Open `template.html` in your favorite code editor
   - Look for the `contentData` object (around line 500-700)
   - Replace placeholder text with your own projects and info
   - Add your own images to the `src/` folder

3. **Adjust the translations** (optional)
   - Find the `translations` object in the script section
   - Update text for all languages you want to support
   - Or just keep English and remove the language switcher

4. **Host it!**
   - Upload to GitHub Pages, Netlify, or any static hosting
   - No build process needed - it's just HTML!

## 🎀 Customization Tips

Want to make it yours? Here are some easy tweaks:

- **Change the default color scheme**: Look for `:root` CSS variables at the top (lines 16-25)
- **Adjust font sizes**: Especially useful for mobile - check the `.lang-ko-style` section if fonts look weird
- **Turn off effects you don't like**: Comment out `initMatrix()` or the trail canvas code
- **Add more language options**: Just extend the `translations` object with your language code

## 🧷 Technical Stuff

Built with:
- Vanilla JavaScript (no jQuery, no React, no nothing - just good old JS)
- CSS3 for animations and effects
- HTML5 Canvas for the Matrix rain effect
- Google Fonts (Press Start 2P, Gothic A1, Diphylleia)

Works on:
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile devices (though the effects work best on desktop)

## 🔝 Unique Characteristics

What makes this template different:

1. **Pixel-Perfect Retro Vibes** - That `image-rendering: pixelated` CSS makes images look crispy like old games
2. **Real-time Theme Editor** - Users can customize colors without touching code
3. **Multilingual from the Start** - Translation system built in, just add your languages
4. **Interactive Canvas Effects** - Not just CSS animations, actual canvas rendering for smoother visuals
5. **No Dependencies** - Everything works standalone, no npm install nightmares

## 🎈 A Few Notes

- The Matrix animation uses requestAnimationFrame, so it shouldn't eat your CPU (much)
- Images are set to `object-fit: cover` so they won't look stretched
- The settings panel saves your preferences in the current session (refresh and they reset - I kept it simple!)
- Modal windows for projects because nobody likes being redirected away

## 🧩 Contributing

Found a bug? Want to add a feature? Feel free to open an issue or submit a pull request! I'm still learning, so any feedback is appreciated.

## 📜 License

MIT License - use it, modify it, make it yours! Just maybe give credit if you keep the Matrix effect, because that took me *way* too long to get right. 😅

## 💰 Future Ideas

Things I might add (or you could add!):
- Dark/Light mode toggle
- More language options
- Save theme preferences to localStorage
- Add more particle effects
- Blog post section with markdown support

---

Made with ☕ and a lot of trial and error. Happy coding!
