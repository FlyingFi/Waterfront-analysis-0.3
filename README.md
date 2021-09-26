This grasshopper definition is designed for urban planners and landscape architects when designing/renovating city's waterfront. It is particularly helpful at the very initial stage of design, when a site is undecided, or when a rough site is chosen and the zoning of the site is to be decided. It shows the existing waterfront condition as well as the condition when new planned waterfront sites are implemented.

**What you need:**

- Grasshopper in Rhino 6 or 7 for either windows or mac.
- Install 'Caribou' (must) & 'Human' (maybe) to allow the definition to work properly.
- Download OpenStreet Map data.

**The final map consisting of layers:**

1. A time-based layer - with your own added zones
2. A base layer - coastline & major railways & waterways
3. A zoning layer - industrial port terminal zones & public waterfront leisure & private waterfront leisure
4. An access point layer - access points at the waterfront from the sea. （This layer is still in development, access points from the land will be added later.)

**Color code of the map**

Blue: industrial port; Red: Public waterfront leisure; Purple: private waterfront leisure

**Note:**

- Some cities may have information missing because of OpenStreet Map feature could be labeled in a different manner, or sometimes it does not have the particular feature recorded. Please cross-check between open street map and rhino, send through a message if there’s such an issue.
- The definition will take around 5mins to load.

**Black boxes in GH**

Those boxes are required to be set with curves or data to allow the definition to work, Other values could be changed based on your needs.
<img width="417" alt="Screen Shot 2021-09-26 at 7 51 17 PM" src="https://user-images.githubusercontent.com/88997408/134806510-4d81cf54-b180-443a-9c35-a0f6d9f38994.png">

**Main functions**

1. Add in main waterfront coastline buffer zones 
![Frame_00000](https://user-images.githubusercontent.com/88997408/134806661-79e0d0e4-714a-4ea1-ae77-3eafcc654d39.gif)

2. 2 ways of setting up planning zone(s) for investigation
Option1: Set a region (polygon) along the waterfront line 
![Screen-Shot-2021-09-26-at-6 03 38-PM](https://user-images.githubusercontent.com/88997408/134806842-8d6344d9-a011-439d-8463-366a10a96836.gif)
Option2: Set your own region(s) - any shape
<img width="1359" alt="Screen Shot 2021-09-26 at 5 59 30 PM" src="https://user-images.githubusercontent.com/88997408/134806894-3ad9a4a5-2982-4be3-9313-d1627283e8dd.png">

3. Show changes of BEFORE and AFTER
![Screen-Shot-2021-09-26-at-5 55 24-PM](https://user-images.githubusercontent.com/88997408/134806906-7bdf08de-e842-479f-af49-4e1ec1850afb.gif)

4. Change zoning proportion of planned zones
![Screen-Shot-2021-09-26-at-7 31 48-PM](https://user-images.githubusercontent.com/88997408/134806915-94a4543f-f14d-460e-968a-5c186e580ee5.gif)
![Screen-Shot-2021-09-26-at-7 33 24-PM](https://user-images.githubusercontent.com/88997408/134806923-4d958196-3ce8-4066-b88d-f06a7b429a8e.gif)

5. Different spatial zoning options with the same ratio made up
![Screen-Shot-2021-09-26-at-7 34 05-PM](https://user-images.githubusercontent.com/88997408/134806927-4a5fce95-f373-4493-b418-03873a2dce71.gif)

**Final map**
<img width="796" alt="Screen Shot 2021-09-26 at 7 43 47 PM" src="https://user-images.githubusercontent.com/88997408/134806803-acafb037-dfae-4158-ab0d-a734d56736d9.png">
