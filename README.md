# Inspire-Page-using-Grid
I used grid to design the layout of the webpage
## Layout
Grid.
I implemented it in the layout of the service catalogue cards.
### Properties
| **Property**                  | **Description**                                                                                                                                       | **Values / Syntax**                                                                                                      |
|-----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------|
| `display`                   | Defines the element as a grid container.                                                                                                             | `grid`, `inline-grid`                                                                                                    |
| `grid-template-columns`     | Specifies the number of columns and their sizes.                                                                                                     | e.g. `auto auto auto`, `1fr 2fr`, `repeat(3, 1fr)`, `100px 200px`                                                         |
| `grid-template-rows`        | Specifies the number of rows and their heights.                                                                                                       | e.g. `auto auto`, `150px 1fr`, `repeat(2, 100px)`                                                                         |
| `grid-template-areas`       | Defines named grid areas using string syntax.                                                                                                        | e.g. `"header header" "sidebar main"`                                                                                     |
| `grid-auto-flow`            | Controls the placement order of auto-placed grid items.                                                                                              | `row`, `column`, `row dense`, `column dense`                                                                             |
| `gap`                       | Shorthand for `row-gap` and `column-gap`.                                                                                                            | e.g. `20px`, `10px 20px`                                                                                                  |
| `row-gap` / `column-gap`    | Sets space between rows or columns individually.                                                                                                     | e.g. `row-gap: 10px; column-gap: 20px;`                                                                                   |
| `justify-content`           | Aligns the entire grid within the container on the inline (horizontal) axis.                                                                         | `start`, `end`, `center`, `space-between`, `space-around`, `space-evenly` :contentReference[oaicite:1]{index=1}             |
| `align-content`             | Aligns the entire grid within the container on the block (vertical) axis.                                                                            | `start`, `end`, `center`, `space-between`, `space-around`, `space-evenly`, `stretch` :contentReference[oaicite:2]{index=2}               |
| `place-content`             | Shorthand for `align-content` and `justify-content`.                                                                                                  | e.g. `center space-between`                                                                                              |
| `grid-auto-rows` / `grid-auto-columns` | Sets default size for rows or columns that are implicitly created (not defined in `grid-template-*`).                                | e.g. `grid-auto-rows: 100px; grid-auto-columns: auto;` :contentReference[oaicite:3]{index=3}                                             |
| `grid`                      | Shorthand for `grid-template-rows`, `grid-template-columns`, `grid-template-areas`, and auto-flow/rows/columns.                                     | e.g. `grid: 150px / repeat(3, 1fr)` :contentReference[oaicite:4]{index=4}                                                   |


### What did I learn?
Grid is the most advanced layout property, so leraning grid helped me build complex layouts in no time. It controls more than one element in a container in 2 dimensions!

