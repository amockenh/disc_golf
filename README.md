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

## Suggesting changes

Anyone can suggest changes. No account is needed.

1. Click **New proposal** to start a draft from the current course, or open a published plan and click **Copy to a draft**.
2. Move tees and baskets, add markers and write notes. The draft saves in your browser.
3. On the **Changes** tab, under **Share your draft**:
   - **Copy share link** gives a link that opens your draft for anyone. Send it to the course team.
   - **Download file** saves the draft as a file you can email.
   - **Submit on GitHub** opens a pull request in this repository (needs a free GitHub account).

Drafts stay in the browser where they were made. Clearing browser data removes them, so share or download anything you want to keep.

Proposals merged into the [`proposals`](proposals/) folder appear on the map as **Published** tabs.

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
| `proposals/` | Community proposals, one file each |
| `assets/` | Site map drawing and aerial photo |
| `vendor/` | three.js 0.128.0 (MIT license) for the 3D view |
