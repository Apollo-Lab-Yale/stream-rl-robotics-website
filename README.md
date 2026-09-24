# An Analysis of Streaming Deep Reinforcement Learning for Adaptive Continual Learning in Robotics

This repository contains the project website for **An Analysis of Streaming Deep Reinforcement Learning for Adaptive Continual Learning in Robotics**.

The page presents:

- An overview and abstract of the work
- Quadruped locomotion adaptation experiments
- Manipulation experiments in Push Cube and Transport Box environments
- Autoplaying task videos and result figures
- Paper, author, lab, and code links

## Preview Locally

The site is a static HTML page. From the repository root, run:

```bash
python3 -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000) in a browser.

Opening `index.html` directly also works for most content, but a local server is recommended for consistent media loading.

## Project Structure

```text
index.html                 Main project page
static/css/index.css       Custom page styles
static/images/             Figures, logos, and favicon assets
static/videos/             Teaser and task demonstration videos
static/js/                 Carousel and slider scripts
```

Task videos are stored in `static/videos/` and include the quadruped Broken Leg, Slippery Floor, and Goal Shift demonstrations, along with Push Cube and Transport Box manipulation demonstrations.

## License

This website is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).
