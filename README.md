# 2026 UNIST PDE Workshop Gwangalli Website

This folder contains a static GitHub Pages website for the 2026 UNIST PDE Workshop Gwangalli.

## File structure

```text
index.html                Korean Home page
schedule.html             Korean Schedule page
en/index.html             English Home page
en/schedule.html          English Schedule page
assets/css/style.css      Design stylesheet
assets/img/unist-logo.svg Temporary UNIST logo placeholder
assets/img/person-placeholder.svg Temporary participant photo placeholder
```

## How to publish with GitHub Pages

1. Create a public repository, for example `unist-pde-workshop-2026`.
2. Upload all files and folders in this directory to the repository root.
3. Go to `Settings` -> `Pages`.
4. Select:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Save and open the displayed GitHub Pages URL.

## Replacing the UNIST logo

Replace `assets/img/unist-logo.svg` with an official UNIST logo image if you have permission to use it. If the file extension changes, update the image paths in the HTML files.

## Replacing participant images

For each participant card, replace the placeholder image path with the corresponding image path, for example:

```html
<img src="assets/img/kwon-bongseok.jpg" alt="권봉석 교수">
```

On English pages inside the `en` folder, use:

```html
<img src="../assets/img/kwon-bongseok.jpg" alt="Prof. Bongseok Kwon">
```

Only use photographs that are publicly available or approved for publication.

## Public information warning

Do not upload internal budget details, private contact information, accommodation room assignments, or other non-public administrative information to the public website.


## 2026-07 update

The Home page now uses the following order: Overview, Event Information, Program, and Key Participants. The Korean page remains the default page, with English pages under the `en/` directory.
