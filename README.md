<img src="https://www.warpdevelopment.com/wp-content/uploads/2023/10/warp-logo-light-3.svg" width="250">

# Vue Assessment:

Create a UI that lists all of the countries in the world using the following API:

https://gitlab.com/restcountries/restcountries

Any libraries or supporting packages of your choice can be used to complete this assessment. For components we would prefer if you used https://www.shadcn-vue.com/

## The UI must:

- Display the countries as a grid, using their flag as the picture with their coat of arms as an icon over their flag.
- Have filters to filter countries by region.
- Have a search to search for a country by common name or FIFA code.
- Have a way to select multiple countries then add them to a favourites list.
- Supply the user with a notification when things happen.
- Favourites must be saved in a pinia store and data must persist to local storage, so that they are not lost when reloading the page.
- The user must be able to click on a country flag that brings up a modal that:
  - Contains basic information about the country such as:
    - Common Name.
    - Region.
    - Fifa code.
    - Population (formatted with thousand separators)
    - Languages.
    - Country local time and time zone.
    - Capital city.
    - A list of their currencies.
    - A link to view on map (either Google or OpenStreetMaps)
  - Have favourite/Unfavourite.
  - Have a close button.
- Have a way to access your favourites page.
  - The favourites page must:
    - Have a list of all my favourite countries.
    - Have a way to unfavourite a country.
    - Have a way to view the details of a country when I click on it using a sub route.
      - The details page must:
        - Have all the same details as the modal on the listing page.
        - A form that:
          - allows the user to make a comment about the country (saved into pinia store against that country)
          - allows the user to optionally add a picture to a comment using a Google images URL.
          - automatically sets the time stamp on each comment formatted as: Thurs, 01 April 2023 10:36AM

## Criteria

The developer will be critiqued on:

- Their ability to understand and use the API.
- Interpretation of the given brief.
- Implementation of typed requests and responses.
- Re-usability of their components and code.
- House keeping of the project. Modules, components and styling.
- Use of pinia store to persist state.
- Their commit history.

## Bonus

- Any features above and beyond whats been outlined
- Styling of the application
- Clear instructions on how to run the application

## Git

Final assessment has to be committed to the developers own GitHub repo, with the url to the repo included in their final email.
