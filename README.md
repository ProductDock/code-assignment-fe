# interview-assignment

### FE React code assignment

### Junior

Assignment:

- You're building simple web application for displaying Ships
  from [SpaceX API](https://github.com/r-spacex/SpaceX-API/tree/master/docs/ships/v4)
- Ships app should have:
    - header with link to home page (/) and theme switch icon for switching between light and dark theme
    - main content with ship cards containing image and basic information about ship (name, type, home_port, year_built, roles),
      additionally if ships is not "active" border of the card should be dashed. There should be maximum three cards in one row.
    - page navigation which should be on the bottom of the page and should have the following behaviour:
      - previous and next buttons
      - previous button is not visible when the first page is active
      - next button is not visible when the last page is active
      - page number should be persisted in the URL (on page refresh last active page should still be active)
 
Ships UI design 
![ships.png](ships.png)

Implementation details and requirements:

- clone the project: <git submodule url>
- project already has some basic setup (prettier, eslint, jest, tsconfig, tailwind config, shadcn)
- use [shadcn](https://ui.shadcn.com/) UI components when developing Ships app
- use Typescript