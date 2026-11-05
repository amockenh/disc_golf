# Brockway Park disc golf course plan

An interactive 3D map of the [Brockway Park](https://udisc.com/courses/brockway-park-aLbz) disc golf course in Rosemount, Minnesota. It shows the course as it plays today and the **2027–2028 course improvement plan**: concrete tee pads, safer walkways, a course map at the entrance, tee signs, wayfinding signs and benches.

**View the map:** https://amockenh.github.io/disc_golf/

## Using the map

- Switch between **Current course** and **Improvement plan 2027–2028** with the tabs at the top.
- Drag to orbit, scroll to zoom and right-drag to pan. **Plan view** gives a top-down view.
- Click any tee, basket or marker to read its notes.
- **Holes** lists each hole's length and elevation change.
- **Changes** lists every change in the plan, with a summary you can copy for estimates. Notes are tagged by plan goal (G1–G6).
- **Site** switches the ground between the drawn site map and the aerial photo.

Positions were traced from the course sign over an aerial photo, with each tee set to UDisc's listed length. Positions and elevations are approximate.

## The improvement plan

1. **Tee pads.** Install concrete tee pads, with minor layout changes where public safety calls for it.
2. **Safe traversing.** Woodchips, class 5 gravel or stairs where walking between holes needs it, with volunteer help.
3. **Course layout map.** A course map at the park entrance.
4. **Tee pad signage.** Functional, consistent tee signs.
5. **Wayfinding signage.** Next-tee arrows, distance-to-basket markers and mandatory play markers.
6. **Benches and rest areas.** Places to sit along the course.

## Updating the site

The plan is edited in the private planning tool, then published here.

1. In the planning tool, open the **Site** tab, choose the layouts to publish and click **Download course.json**.
2. In this repository, open the `data` folder, choose **Add file → Upload files** and upload the new `course.json` to replace the old one.
3. Commit. GitHub Pages updates the map within a minute or two.

## Files

| Path | What it is |
|---|---|
| `index.html` | The map page |
| `data/course.json` | Layouts, tees, baskets, markers and notes |
| `assets/` | Site map drawing and aerial photo |
| `vendor/` | three.js 0.128.0 (MIT license) for the 3D view |
