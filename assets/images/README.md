# Image slots

All imagery is stored as PNG. To swap in your own photography or 3D renders, replace a file and keep the **same file name**.
Sizes are targets; any size works, but keep the aspect ratio.

| Folder | Files | Ratio / size | Used on |
|---|---|---|---|
| `welcome/` | `hero.png` | 9:16 portrait, dark background | Welcome screen (text sits on the bottom 45%) |
| `onboarding/` | `slide-1.png`, `slide-3.png` (9:16, dark), `slide-2.png` (square, transparent PNG of a plate) | | Onboarding slides |
| `auth/` | `bg.png` | 9:16, light background (top 44% is shown) | Sign in / Sign up |
| `workouts/` | `fat-burn-hiit`, `upper-body-power`, `leg-day-burn`, `core-crusher`, `morning-flow`, `cardio-blast` `.png` | 10:7 landscape, figure centred | Workout list, cards, detail header, player, exercise thumbnails |
| `categories/` | `all`, `hiit`, `strength`, `core`, `yoga`, `cardio` `.png` | 1:1, 200 px | Reserved category thumbnails |
| `meals/` | `bowl`, `oats`, `salad`, `eggs`, `shake`, `banana`, `rice`, `wrap`, `yogurt`, `default` `.png` | 1:1, 256 px, shown as circles | Meal rows and quick-add sheet. `default.png` is used for every custom meal |
| `home/` | `nutrition.png` (1:1, transparent plate), `challenge.png` (2:1, dark) | | Empty states, challenge banner |
| `profile/` | `avatar.png` | 1:1, 256 px | Header and profile avatar |
| `badges/` | `first-workout`, `three-workouts`, `hydrated`, `logged-meals`, `kcal-500`, `challenge` `.png` | 1:1, 256 px, circular with transparent corners | Progress → Achievements (locked badges are greyed out automatically) |

Style: white clay mannequin with red / blue muscle heat-map, soft floor shadow, neutral studio background.

## App logo (`assets/img/`)

| File | Size | Used for |
|---|---|---|
| `logo.png` | 256 px, rounded tile | Header brand, auth, onboarding, analysing screen |
| `logo-512.png` | 512 px, rounded tile | Splash screen |
| `logo-green.png`, `logo-green-512.png` | rounded white tile, green mark | Light backgrounds |
| `og.png` | 1200 × 630 | Link previews |

Logos are real PNG files. Keep the `.png` extension; a PNG saved as `.svg` will not render in browsers.
