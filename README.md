# Dote matchmaking dashboard

A static dashboard for exploring fictional matchmaking profile data.

## GitHub Pages

In this repository, open **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, choose **main** and **/(root)**, then save. The site will be available at https://gingercat-del.github.io/test/ after GitHub finishes publishing.

## Data

`sample-profiles.csv` is the source loaded on page opening. It contains fictional examples. To update the public sample, export the `Profiles` worksheet from `sample-profiles.xlsx` to CSV, preserve the existing column headers, and replace `sample-profiles.csv` in this repository.

The **Upload Excel or CSV** control previews a local `.xlsx`, `.xls`, or `.csv` file in the current browser session. Uploads are not stored online or shared with other visitors. Excel parsing uses an external SheetJS script; CSV works without it.

This static version has no sign-in, shared editing, real matching algorithm, or backend database. Do not publish personal matchmaking data in the public sample CSV.
