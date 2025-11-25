# Do You Love Me?

A small, playful interactive web micro-project that asks "Do you love me?" with evasive "No" behavior, a heart-loader animation, and a celebratory result. Ideal as a lightweight demo of DOM manipulation, CSS animations, and playful UX.

## Demo

Open [index.html](index.html) in a browser to try the demo.

## Features

- Evasive "No" button that avoids the cursor (fun interactive behavior).
- Smooth heart-loader built with pure CSS animations.
- Result view displays a looping video (`cute-love-gif.mp4`) when the user chooses "Yes".
- Lightweight: zero build tools, plain HTML/CSS/JS.

## How it works quick

- The UI is defined in [index.html](index.html).
- Interaction is implemented in [js/script.js](js/script.js) which exposes these key variables:
  - [`questionContainer`](js/script.js)
  - [`resultContainer`](js/script.js)
  - [`gifResult`](js/script.js)
  - [`heartLoader`](js/script.js)
  - [`yesBtn`](js/script.js)
  - [`noBtn`](js/script.js)

The "No" button moves on `mouseover` to random positions inside the question container. Clicking "Yes" hides the question view, shows the heart loader for 3 seconds, then reveals the result container and plays the video.

## Project structure

- [index.html](index.html) - Entry page and layout.
- [css/styles.css](css/styles.css) - All styles and animations.
- [js/script.js](js/script.js) - Interaction logic.
- cute-love-gif.mp4 - Result video (place in project root).

### Installation and Usage

1. Clone or download this repository.
2. Ensure `cute-love-gif.mp4` is in the project root (or update the path in [index.html](index.html)).
3. Open [index.html](index.html) in any modern browser (no server required).

### Github:

1. **git clone:**

```
git clone https://github.com/md-abu-kayser/do-you-love-me.git
```

2. **git pages link:**

```
https://md-abu-kayser.github.io/do-you-love-me/
```

### Customization Ideas

- Add accessibility improvements (keyboard support and ARIA attributes).
- Make the "No" button movement constrained to visible bounds to avoid overflow.
- Replace the video with an optimized GIF or WebM for smaller size.
- Add responsive size tweaks for smaller screens.

### License

- This project is licensed under the terms of the **[MIT License](./LICENSE)**.
- You may replace or update the license as needed for client or proprietary projects.

---

### Contact and Maintainer

**Maintainer:** [md-abu-kayser](https://github.com/md-abu-kayser)  
**Name:** Md Abu Kayser - Full-Stack Engineer

- **GitHub:** [github.com/abu.kayser-official](https://github.com/md-abu-kayser)
- **Email:** [abu.kayser.official@gmail.com](mailto:abu.kayser.official@gmail.com)
- **Project:** _Do You Love Me?_

If you’d like this README tailored for a specific purpose - such as **hiring managers**, **open-source contributors**, or **client deliverables** - feel free to request a custom tone or format.

---

### Contributing

**Small tweaks and UX improvements are welcome. Fork the repo, create a feature branch, and open a PR.**

**Thank you for reviewing this project!**

---
