# Waterfront-analysis-0.3
This grasshopper definition is for site analysis/mapping of a city waterfront. It helps architects, landscape architects and urban planners to understand waterfront condition and identify opportunities for intervention.

**What you need:**
- Grasshopper in Rhino 6 or 7 for either windows or mac.
- Install 'Caribou' (must) & 'Human' (maybe) to allow the definition to work properly.
- Download OpenStreet Map data, suggested file size of 50MB (make sure the OpenStreet Map data is good quality, otherwise it does not work well)

**The result map consisting layers of:**
- A base layer - coastline & major railways & waterways
- A zoning layer - industrial port terminal zones & public waterfront leisure & private waterfront leisure
- An access point layer - access points at the waterfront from the sea. （This layer is still in development, access points from the land will be added later.)
- Color code of the map - Blue: industrial port; Red: Public waterfront leisure; Purple: private waterfront leisure

**Note:**
- Some cities may have information missing because of OpenStreet Map feature could be labeled in a different manner, or sometimes it does not have the particular feature recorded. Please cross check between open street map and rhino, send through a message if there’s such an issue.
- The definition can be very slow when first loading. We are still trying to fix this issue for our next version. For an osm file size around 50 MB, it took around 15-20mins to load. If you are using a large map, please select a small region to test out whether the definition works properly first.
- A bake function will be developed in a later version.

**Map Example:**

Singapore waterfront map:

<img width="444" alt="Singapore waterfront map" src="https://user-images.githubusercontent.com/88997408/130386739-002c0ccc-8d5d-49f0-aa32-ea3569776b8c.png">

Kobe waterfront map:

<img width="539" alt="Kobe waterfront map" src="https://user-images.githubusercontent.com/88997408/130386771-a33e69f6-01e4-4c89-91d4-4361b283bb92.png">

**Grasshopper file:**

Please refer to the release.
