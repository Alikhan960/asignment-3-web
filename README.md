# Gold Gym - Web Assignment #3 (Media Queries + Bootstrap Grid)

Responsive six-page fitness club website created by **Yelnur Akhmetzhan, Akejan Ahmetov and Alikhan Yertaiuly** (AITU, SE-2504).

## Pages

| Page | File | Assignment features |
| --- | --- | --- |
| Home | `index.html` | Responsive typography, CSS-only 3-card group (Task 2), Bootstrap grid hero |
| About | `about.html` | Two-column grid (`col-lg-6`), three Bootstrap cards |
| Prices | `prices.html` | Responsive table, `btn-group`, button sizes and disabled state |
| Trainers | `trainers.html` | Bootstrap card grid (`row-cols-*`) |
| Locations | `locations.html` | Nine-image carousel, three-column grid (`col-lg-4`), `container-fluid` |
| Contact | `contact.html` | Bootstrap form: `form-control`, `input-group`, `form-select`, radio buttons, checkbox |

## Technologies

HTML5 semantic elements, CSS media queries (breakpoints 576 px and 992 px), CSS Grid, Bootstrap 5.3.3 from the official CDN (grid, spacing utilities, navbar, buttons, carousel, cards, form controls).

## Structure

```
index.html  about.html  prices.html  trainers.html  locations.html  contact.html
css/styles.css
images/
```

## How to run

Open `index.html` in a browser (internet is needed for the Bootstrap CDN), or publish the repository root with GitHub Pages (Settings, Pages, Deploy from a branch, `main`, `/ (root)`). All project files use relative paths.

## Accessibility

Semantic `header`, `nav`, `main`, `section`, `article`, `aside`, `footer`; `alt` text on every image; `label` for every form field; `aria-label` on the navigation and its toggle button; visually hidden text on carousel controls; text contrast is above 6.8:1 everywhere.
