# User Stories and Acceptance Criteria

## Essential
* As a user, I want to know what this app is about.
    * A header component is rendered with an h1 of the app title.
* As a user, I want to find five options to have a margarita so that I can decide where to go.
    * When #findDrinks is clicked, a ul of at least 5 list options renders.
* As an alcoholic, I need to find the closest margarita nearby, so I don't waste my drinking time.
    * When #findDrinks is clicked in Denver city limits, all results are within a 5-mile radius.
    * If geo-location is disabled, user receives an error prompting them to enable geo-location and try again.
    * The 5+ list options are sorted by proximity (least to greatest distance).
* As a user, I want to see the results on a map, so that I can know how to get there.
    * If geo-location is disabled, user receives an error prompting them to enable geo-location and try again.
    * If geo-location is enabled, a canvas element is present in the DOM above the list.
    * If geo-location is enabled, on load, map is centered at user's location.
    * If geo-location is enabled, there are at least 5 pin images on the rendered map.
* As a user, I want to see more information when interacting with the map, so that I know stuff without having to navigate elsewhere.
    * Each pin renders an info bubble on click.
    * Each info bubble includes an h2 with the establishment name and img with the rating.
    * Each bubble is dismounted from the DOM when the "X" icon is clicked.
* As a user, I want to see a complete establishment profile without changing window location, so that I can browse quickly.
    * Each info bubble includes an h2 with the establishment name, an img with the rating, and an anchor tag containing "More Info."
    * When the anchor tag is clicked, a modal renders over the page with the page darkened in the background.
    * The DOM is still intact behind the modal.
    * The modal includes an h2 with the establishment name, an img with the rating, a p-tag with the address, a p-tag with phone number, a p-tag with hours, a p-tag with website link, a p-tag with marg description (or p-tag with "No Description Available").
    * The modal h2 specifying establishment name matches the info bubble's h2 specifying establishment name.
    * The modal img specifying star rating matches the info bubble's img specifying star rating.
* As a working professional, I want to find a location for a margarita on my desktop from work, so I can get get a specific drink with my co-workers.
    * *__will determine later__*
* As a user, I want to add new location for a margarita, so that others can find it.
    * When clicking on #addMarg in the header, a modal with a form is rendered over the page the page darkened in the background.
    * The DOM is still intact behind the modal.
    * The form includes inputs for establishment name, rating, and address.
    * When "Machete" is typed in the name input, 5 is typed into the rating input, "2817 E 3rd Ave" is typed into the address input, and #submitForm is clicked, a spinner will render temporarily and a p-tag will render below #submitForm with the text "Marg added successfully."
    * When making a GET request to the server, Machete is returned with its 5-star rating and "2817 E 3rd Ave" address.
* As an opinionated person, I want to give a star rating on a margarita I drank so that I can have my voice be heard.
    * 
* As a beverage connoissier, I need to find the highest rated margarita nearby, so that I don't waste my money on lower quality margaritas.

## Desired
* As an opinionated person, I want to leave a text review of a margarita I drank  so that I can have my voice be heard.
* As an alcoholic, I need to find the cheapest margarita nearby, so I don't waste my drink money.
* As a tourist, I want to find five options for a nearby margarita so that I can have one in an unfamiliar city.
* As a user, I want to see a map of an individual establishment on its profile modal.