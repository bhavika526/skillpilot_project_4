# SkillPilot Project 4 - Responsive Image Gallery

A simple gallery web page built as part of my SkillPilots program. The page loads different image sizes depending on the screen width, using the `<picture>` element and `srcset`.

## Features

- Gallery of 6 images laid out with CSS Grid
- `<picture>` element with multiple `<source>` files for each image
- Large image for desktops, medium image for tablets, and small image for phones
- Responsive layout: 1 column on phones, 2 columns on tablets, and 3 columns on desktops
- Image captions using `<figure>` and `<figcaption>`
- Alt text and fixed width and height on every image

## How the Images Change

| Screen width | Image size loaded |
|---|---|
| 1024px and above | Large (1200 x 800) |
| 600px to 1023px | Medium (800 x 533) |
| Below 600px | Small (480 x 320) |

## Technologies Used

- HTML5 (`<picture>`, `<source>`, `srcset`)
- CSS3 (CSS Grid and media queries)

## How to Run

1. Download or clone this repository.
2. Open `index.html` in any web browser. An internet connection is needed because the images are loaded from [Picsum Photos](https://picsum.photos).
3. Make the browser window narrower and wider to see the layout change.
4. To see the different image files load, press **F12**, open the **Network** tab, and refresh the page.

## Project Structure

```
skillpilot_project_4/
├── index.html
└── README.md
```

## Acknowledgement

Created as part of the SkillPilots program. Images are provided by Picsum Photos.
