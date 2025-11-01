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
https://github.com/go-kawser/Do-You-Love-Me.git
```

2. **git pages link:**

```
https://go-kawser.github.io/Do-You-Love-Me/
```

### Customization Ideas

- Add accessibility improvements (keyboard support and ARIA attributes).
- Make the "No" button movement constrained to visible bounds to avoid overflow.
- Replace the video with an optimized GIF or WebM for smaller size.
- Add responsive size tweaks for smaller screens.

### Contributing

**Small tweaks and UX improvements are welcome. Fork the repo, create a feature branch, and open a PR.**

#### License and Contact

**MIT - see [LICENSE](LICENSE).**
**Email:** abu.kayser.official@gmail.com
