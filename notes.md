<h1>Project Inspo</h1>

- Dani Moodboard: https://www.pinterest.ca/colombia2011409/experimental-waves-moodboard/
- Dani Inspo: https://www.thinkingbox.com/
- Pat Inspo: https://planets.teamlab.art/tokyo/

<h1>Three.js Inspo</h1>

- START HERE: https://jsfiddle.net/f2Lommf5/
- Procedurally Generated Minimal Environment: https://codepen.io/marctannous/pen/RNGjmz
- Realistic Water: https://codepen.io/Khangeldy/pen/pgXNMZ
- Bloom effect: https://threejs.org/examples/?q=bloom#webgl_postprocessing_unreal_bloom_selective/
- Light Trails: https://tympanus.net/codrops/2019/11/13/high-speed-light-trails-in-three-js/
- Trails: https://github.com/mrdoob/three.js/blob/master/examples/webgl_trails.html
- Web Trails: https://threejs.org/examples/?q=trail#webgl_trails
- Water ripples + vertex shaders: https://blog.mozvr.com/water-ripples-with-vertex-shaders/
- Intermediate tutorials: https://medium.com/@joshmarinacci/threejs-intermediate-skill-tutorials-b48e49e37606

- Examples:
Art of Noise: https://codepen.io/Tibixx/pen/rNaKLZW?editors=1111
- has darkness, colors, pulsating ground floor,,
- raycasting modulates waves in area of mouse
- OrbitControls for box:
- Import via modules: https://threejs.org/docs/#manual/en/introduction/Import-via-modules

<h3>Weblinks</h3>
Instagram: https://www.instagram.com/exp.wavs/

Web Performance links:
Expires headers for caching photos: https://gtmetrix.com/add-expires-headers.html
Expires headers word of caution: https://moz.com/blog/expires-headers-for-seo-why-you-should-think-twice-before-using-them
Website speed test: https://tools.pingdom.com/#5c068f52b2c00000
Smoothing: Lerp: http://www.rorydriscoll.com/2016/03/07/frame-rate-independent-damping-using-lerp/

Use webpack to bundle links: https://webpack.js.org/

Google Form Custom Design https://blog.webjeda.com/google-form-customize/

<h3>Generative Art</h3>
Matt DesLauriers: https://www.youtube.com/watch?v=8Uo6zFwSO78
Simple Wave Generative: https://www.hailpixel.com/articles/generative-art-simple-mathematics
Joanie Lemercier: https://joanielemercier.com/
13kb web game // Matt DesLauriers: https://mattdesl.svbtle.com/bellwoods
Pseudo-Random Number Generator: https://www.npmjs.com/package/seed-random
Web-Audio Scheduling: https://www.html5rocks.com/en/tutorials/audio/scheduling/
Web-Audio Games: https://www.html5rocks.com/en/tutorials/webaudio/games/







BUILD NOTES:

FEEDBACK SESSION Feb 22, 2020
* have mouse position affect intensity and brightness, and movement
* overall slower, chiller, less distracting
* logo overlay
* max really likes tilt idea: logo tilt / position
* glitch comet trails? over mouse?


Okay so I put the <a href="img/logo.png"> into Adobe Illustrator 2019CC and discovere the color is:
COLOR: #d6b513
Its not a webcolor so I may need a workaround for that later. I managed to pull out the svg by
1. rasterizing the logo to reduce the size
2. using Edit -> color to make it grayscale, then black
3. Edit -> image trace and expanded
4. export the file as .svg and place within /img/ folder

Now, I just pushed the latest version of the code to github, and ran the website on my phone. A few issues I'm noticing.
Issues:
* The first should be simple: disable scroll bar and enable touch tracking so the visual is interactive.
* Colors are wildly different. This seems to be a huge problem, as all monitors are super different and so color calibration becomes a thing. Will read further on this later. https://discourse.threejs.org/t/whats-this-about-gammafactor/4264
