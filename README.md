##Requirements:
- Auto Complete Box - but keep the same look and feel as the current site.
- Search results will be listed in geolocation by distance - keeping the same look and feel as the current website.
- Camden will provide the lat/long for each location(metros, neighborhood)
- Poetic web developer will need to integrate the Algolia search
- Dependent on Camden vetting Algolia and committing to service
- Regional landing pages - where people are sent from a search engine or direct link to search results - will also need to communicate with Algolia to list results by distance

#Goals:
- Goal 1: Geo Sorting of results(metros, communities, neighborhood).
- Goal 2: New search page with updated search UX and Map/Cards on the same page (like Airbnb, apartment list)

##UI:
- New search design (we have assets Poetic).
- New map layout (we have assets Poetic).
- New Regional landing pages(we have assets Poetic). 
- Time ?

##Drupal:
- Remove taxonomy tree (view).
- Add geo field to taxonomy (metros, neighborhoods).
- Time ?

##Search API:
- Create a Search API Index.
- We have to define which fields will be indexed.
- Define Workflow.
- Index Content.
- Time ?

##Algolia module:
- algorithm for grouping neighborhoods.
- Fuzzy search
- Return Typeahead results in order of closest match, not alpha order
- Return Search Results by Geo Location
- Ability to search by full state name, not just abbreviation (ie California instead of just CA).
- The dropdown list should be longer so you can see more results at one time.
- Create a separate index ?. 
- Maintaining second index ?.
- Time ?

**Notes:** Implement functionality for proof of concept, then after all cases have been evaluated start adding UI.
