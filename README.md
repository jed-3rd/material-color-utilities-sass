# Material Color Utilities: SASS

A SASS library based on Google's [material-color-utilities](https://github.com/material-foundation/material-color-utilities)

Algorithms and utilities that power the Material Design 3 (M3) color system, including choosing theme colors from images and creating tones of colors; all in a new color space.

## Getting Started

_*TO DO*_

## Usage

### Cheat sheet

<a href="https://github.com/material-foundation/material-color-utilities/raw/main/cheat_sheet.png">
    <img alt="library cheat sheet" src="https://github.com/material-foundation/material-color-utilities/raw/main/cheat_sheet.png" style="max-width:640px;" />
</a>

### Components

The library is composed of multiple components, each with its own folder.

| Components       | Purpose                                                                                                                                                                                             |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **blend**        | Interpolate, harmonize, animate, and gradate colors in HCT                                                                                                                                          |
| **contrast**     | Measure contrast, obtain contrastful colors                                                                                                                                                         |
| **dislike**      | Check and fix universally disliked colors                                                                                                                                                           |
| **dynamiccolor** | Obtain colors that adjust based on UI state (dark theme, style, preferences, contrast requirements, etc.)                                                                                           |
| **hct**          | A new color space (hue, chrome, tone) based on CAM16 x L\*, that accounts for viewing conditions                                                                                                    |
| **palettes**     | Tonal palette — range of colors that varies only in tone <br>Core palette — set of tonal palettes needed to create Material color schemes                                                           |
| **quantize**     | Turn an image into N colors; composed of Celebi, which runs Wu, then WSMeans                                                                                                                        |
| **scheme**       | Create static and dynamic color schemes from a single color or a core palette                                                                                                                       |
| **score**        | Rank colors for suitability for theming                                                                                                                                                             |
| **temperature**  | Obtain analogous and complementary colors                                                                                                                                                           |
| **utilities**    | Color — convert between color spaces needed to implement HCT/CAM16 <br>Math — functions for ex. ensuring hue is between 0 and 360, clamping, etc. <br>String - convert between strings and integers |

## Background

- [The Science of Color & Design - Material Design](https://material.io/blog/science-of-color-design)
- [Material's material-color-utilities Offical Libraries](https://github.com/material-foundation/material-color-utilities/blob/main/README.md?plain=1)
- [Material 3 Homepage](https://m3.material.io/)

## Dependencies

- [SASS-Bitwise](https://github.com/jed-3rd/sass-bitwise) - Used to preform the necessary bitwise pperations for some color shifts.
