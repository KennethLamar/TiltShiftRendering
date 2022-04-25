# Tilt-Shift Rendering Using a Thin Lens Model

This project implements a tilt-shift camera lens. It is based on [*Tilt-Shift Rendering Using a Thin Lens Model*](Kensler2021_Chapter_Tilt-ShiftRenderingUsingAThinL.pdf), a paper written by Andrew Kensler and published in [Ray Tracing Gems II](https://link.springer.com/content/pdf/10.1007%2F978-1-4842-7185-8.pdf). Included are interactive slides created using [reveal.js](https://revealjs.com/), an interactive 2D demo made using [D3.js](https://d3js.org/), and an interactive 3D render using [TWGL](https://twgljs.org/).

## [Interactive Slides](https://kennethlamar.github.io/TiltShiftRendering/)

## [Interactive Demo](https://kennethlamar.github.io/TiltShiftRendering/sliderDemo.html)

### [Original Author Shadertoy Demo](https://www.shadertoy.com/view/tlcBzN)


## Setup

Some assets will not load in development without using a local test server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install [Node.js](https://nodejs.org/) (10.0.0 or later)

1. Clone the reveal.js repository
   ```shell
   $ git clone https://github.com/hakimel/reveal.js.git
   ```

1. Move to the reveal.js folder and install dependencies
   ```shell
   $ cd reveal.js && npm install
   ```

1. Serve the presentation and monitor source files for changes
   ```shell
   $ npm start
   ```

1. Open <http://localhost:8000> to view your presentation
