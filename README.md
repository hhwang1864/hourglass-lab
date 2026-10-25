# Hourglass Lab — planning document

Open `plan.html` directly in a browser. Edit the folder in Zed.

This stage contains an HTML/CSS plan with a static SVG concept drawing, worked examples, mathematical explanations, source links, and proposed milestones. The expandable sections use native HTML. There is no JavaScript, application runtime, build step, or simulation implementation.

The planned project is a wooden 3D hourglass with 50,000 grains initially and a measured stretch target of 500,000. Proposed configuration covers dimensions, grain size/count, sand and wood colours, glass thickness/density/optics, gravity and simulation speed.

The implementation language and platform remain undecided. A JavaScript/TypeScript application stack is excluded. The browser is a possibility to evaluate, not a settled requirement.

The mathematics covers units and transforms, a surface of revolution and its volume, packing and mass, true signed distances versus implicit shape functions, collision projection, PBD/XPBD, spatial neighbour searches, granular discharge, glass optics and failure, and reproducible GPU benchmarks.

The diagram is schematic. Worked-example values use the explicitly defined mathematical profile. No GPU performance has been measured yet.

GitHub CLI is signed in as `hhwang1864`. Git author email is `hhwang1864@gmail.com`. No remote repository has been created or published.
