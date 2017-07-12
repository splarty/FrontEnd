[//]: # (Image References)
[image_0]: Landing.jpg
[image_1]: pinClick.jpg
[image_2]: menuClick.jpg
[image_3]: responsive.gif
[image_4]: synchronousQuery.jpg
# Neighborhood Map Project

The _Neighborhood_ for this map covers the Stadia where Liverpool F.C., an English football team, will play all of their 38 _Premier League_ games this season.

## Landing Page

![alt text][image_0]

### Contents

The _Landing Page_ contains:

- A map of the British Isles with pins located at the football stadia where Liverpool F.C. will play _Premier League_ games this season.

- A side bar containing a searchable list of the opponents that Liverpool F.C. will play and the dates that the games take place. The list is searchable by opponent and month.

- Buttons that:

  - Toggle the sidebar display

  - Reset the map to a map of the British Isles

  - Take you to _Anfield_, the home stadium of Liverpool F.C.

## Functionality

![alt text][image_1]

There are two ways to navigate this web application:

- Clicking directly on the pins, which results in a popup including:

  - A streetview of the stadium for the relevant pin.

  - Details about the teams, derived from an asynchronous query (api.football-data.org), including the score of the game (currently, they are all _N/A : N/A_).

  - For the benefit of the reviewer, this is what a asynchronous query looks like:

  ![alt text][image_4]

- Searching and clicking on team name in the sidebar. This results in:

  - The map location changes to a close up of the relevant stadium.

  - The same popup as above.


  ![alt text][image_2]

## Responsive

The application is responsive. As seen below:

  ![alt text][image_3]
