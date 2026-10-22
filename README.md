# Jiaming Huang — Engineering Portfolio (minimal case-study design)

Static GitHub Pages website. The STAIR and E-Ducati-On case-study pages have a restrained, documentation-style design using a white background, readable text, real project photos, and technical figures.

## What's new in this revision

- STAIR and E-Ducati-On detail pages redesigned to a plain academic/engineering layout.
- E-Ducati-On: full 66-second demonstration embedded within the Evaluation section. The MP4 has **no audio track** and is compressed to ~8.5 MB so it can be uploaded through GitHub's website.
- Both detail pages keep their previous project descriptions, team-vs-individual contribution distinctions, results and limitations.
- An in-page section navigation provides quick links to Overview, My work, Evaluation, and Takeaways.
- The homepage, Spot and Tencent descriptions, and the current resume PDF are retained from the previous site package.

## Deployment (existing `Jerry031902/Portfolio` repository)

1. Unzip this archive on your computer.
2. Go to GitHub > `Jerry031902/Portfolio` > Code > Add file > Upload files.
3. Drag **the contents of the unzipped folder** into the upload area. Drag folders from File Explorer to preserve subdirectories.
4. Confirm that `projects/stair.html`, `projects/e-ducati-on.html`, and `assets/projects/ducati/education-demo-muted.mp4` have the expected paths.
5. Commit the changes to `main`. GitHub Pages deploys automatically; don't unpublish/reconfigure it.

If another coding tool (e.g. Codex) has already changed the homepage or `styles.css`, instead use the separate **project-only integration ZIP**. It updates project pages, project-specific CSS, and their media without overwriting homepage work.

## Video note

The original uploaded `Education_full-video.mp4` contained sound and was about 152 MB. The embedded version retains the full duration (~66 s), but removes all audio and reduces the resolution to 1280×720 for web delivery. It does not autoplay.
