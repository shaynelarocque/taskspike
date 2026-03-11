# TaskSpike

A skeuomorphic kanban board inspired by restaurant kitchens. Tasks hang from metal ticket rails as thermal receipt paper. Completed tickets get skewered onto a receipt spike.

Built as a single HTML file. Uses localStorage. Purely an experiment in CSS textures and drag-and-drop.

**[Live demo](https://shaynelarocque.github.io/taskspike/)**

## How it works

- **To Do** and **In Progress** columns are horizontal ticket rails (max 6 per rail)
- Drag tickets between rails or onto the spike tip to mark them done
- The spike holds up to 6 completed tickets before the recycling bin kicks in
- Click the bin to clear the spike manually

## Details

- Brushed metal effects based on [simurai's CSS metal technique](https://codepen.io/simurai/pen/kvyEeg)
- Receipt paper textures with randomized crumples, creases, torn edges, coffee stains, and tape strips
- Spike base uses radial brushed metal with perspective transform
- Completed tickets slide down the spike with a bounce animation
- Fly-to-bin recycling animation with staggered timing
