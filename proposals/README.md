# Proposals

Each `.json` file here is a course-change proposal made on the public map. Once a proposal is merged into `main`, it appears on the site as a **Published** tab, with its own Changes list and summary.

## How proposals arrive

- **Pull requests.** On the map, someone clicks **Submit on GitHub** in their draft. GitHub opens a new file in this folder, and the person commits it as a pull request.
- **Share links and files.** People without a GitHub account send a share link or a downloaded draft file to the course team. To add one, open the link, or use **Open draft file**, then click **Submit on GitHub**. You can also upload the downloaded file to this folder.

## Reviewing a proposal

1. Open the pull request and read the description.
2. To see the proposal on the map before merging, open the pull request's **Files changed** tab, then **View file**, and **Download raw file**. On the public map, click **Open draft file** and choose it.
3. Discuss in the pull request's comments. Merge it to publish the proposal, or close it to decline.

## File format

`brockway-proposal/1`: a name, an optional author and description, the layout it's based on (`current`), and the list of tees, baskets and markers. The site checks every value when it loads a file, so a broken or edited file can't break the map.
