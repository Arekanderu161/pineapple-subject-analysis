# Surveillance subject analysis — original prompt

Source image: `source.png` — the supplied pineapple artwork (499 × 374).

## Original request

Turn the attached image into a seamless looping GIF (~15s, 15fps)
styled as a surveillance-camera "subject analysis" sequence:

1. ACQUIRE – desaturated CCTV feed with REC, camera ID, running
   timecode; a search reticle locks onto the subject.
2. SILHOUETTE – background dims to a dark grid; AI detection boxes
   (head, torso, limbs + confidence scores) pop in; a scan line
   turns the subject into a flat silhouette.
3. STRUCTURE – silhouette becomes a glowing wireframe (edges +
   triangle mesh), then a pose skeleton with joint angles.
4. FEATURES – real colors return; an "ENHANCE" zoom on the face;
   animated callouts with typed labels for 4–5 key features.
5. PALETTE – extract the 6 dominant colors (k-means); swatches fly
   from the image into a panel with hex codes and percentages.
6. IDENTIFY – "TARGET LOCKED" + ID card (class, threat level,
   match %), then a glitch back to frame 1 for a seamless loop.

Keep the original artwork intact (segment it, don't redraw it).
Minimal HUD: white + one accent color, monospace font, a stage
progress panel in the emptiest area of the frame, no text over
the face. Export GIF + MP4.

## Approved adaptation to the supplied subject

- The subject is a pineapple: crown, body, and base replace human anatomy.
- ENHANCE magnifies an original crop of the rind; it does not invent a face.
- Five feature callouts: spiked crown, diamond eyes, gold rind, ovoid body,
  and rounded base.
- The silhouette and edge map use the segmented original pixels. The mesh
  is clipped to the subject, and its structural skeleton shows measured
  angles between graphic landmarks.
- The six colors and percentages are computed with RGB k-means over the
  foreground mask. Detection confidence, match, and threat are simulated
  interface values.
- Use white and mint (#63F5DD) HUD graphics with a monospace font. Keep the
  stage panel in the empty left portion and feature panels on the right.
- Preserve the artwork without generative redrawing. Create 225 frames at
  15 fps, 15 seconds total. Export an infinitely looping GIF and a loop-ready
  silent H.264 MP4 at 998 × 748.
- End with a short glitch reset into the exact initial composition.

## Delivered files

- `pineapple-subject-analysis.gif`
- `pineapple-subject-analysis.mp4`

The sequence was implemented through programmatic compositing of the
original artwork, not through an image/video generation model.
