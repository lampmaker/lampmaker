## Hi, I'm Matthijs Keuper 👋

I'm an engineer and an artist, and most of what's here sits on the line between the two.

**The engineer:** about thirty years with light. LED systems, nonimaging optics, photobiological safety, and taking
hardware to production at Philips, Lumileds and my own companies, with 25+ patents along the way.

**The artist:** studio **[code+wood](https://codeandwood.art)**. I turn digital logic into something physical.
- **Wood engravings.** An AI portrait or a 3D-rendered night street, turned into a dense field of lines by my own
  generative JavaScript, laser-engraved into black wood on a laser cutter I built, then filled by hand with oil paint
  I mix from linseed oil and pigment. Up close it's a tangle of lines; step back and a face looks at you.
- **Wood relief prints** in small editions, pressed by hand on a 60-year-old Korrex proof press.
- **Generative work**: *Trajectories*, *Linea (non) Recta* on fx(hash), and flow and erosion simulations that sculpt
  landscapes in real time.
- **Vinny**, a six-axis robot I'm teaching to paint.

The two halves feed each other. The erosion landscapes needed a path tracer, and what I learned from it is in the
design of the one below.

### [ShadyTracer](https://github.com/lampmaker/ShadyTracer)

**Physically based light in the browser.** A WebGPU path tracer that renders in real units, candela per square metre
and lux, with a scene builder, a measuring tool, and an optics bench for LED and luminaire design that traces the same
scene the picture shows. Nothing to install: it runs on your own graphics card. I think good optical tools shouldn't
need an expensive licence and a workstation.

**[Run it →](https://shadytracer.com)**

<!-- Once docs/screenshots/hero.png is on ShadyTracer's main branch, delete this line and the one after it to show it.
![ShadyTracer: the scene tree, properties and library on the left, the picture in the middle, the renderer's settings on the right](https://raw.githubusercontent.com/lampmaker/ShadyTracer/main/docs/screenshots/hero.png) -->

### Also here

- **[tinywebgpu](https://github.com/lampmaker/tinywebgpu)**: one file, no dependencies, no build step. A WebGPU
  micro-framework for shader-first work (SDF tracers, GPGPU experiments, shadertoy-style pieces). ShadyTracer runs on it.
- **[GUISTUFF](https://github.com/lampmaker/GUISTUFF)**: UI widgets built on [Tweakpane](https://cocopon.github.io/tweakpane/):
  a property table, a tree view and a split-pane container.
- **[CODEANDWOOD-TOOLKIT](https://github.com/lampmaker/CODEANDWOOD-TOOLKIT)**: the studio's JavaScript utilities
  for arrays, colour, SVG and paths.
- **[TSON](https://github.com/lampmaker/TSON)**: JSON with tables, matrices and unquoted keys. Every JSON file is valid TSON.

### Support

ShadyTracer is free and stays free, for students, makers, artists and anyone curious about light. If it's useful to
you, a tip keeps it going, one-time or monthly: **[♥ Sponsor on GitHub](https://github.com/sponsors/lampmaker)**.
Or hang one of my pieces on your wall: **[codeandwood.art](https://codeandwood.art)**.
