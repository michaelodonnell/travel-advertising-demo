DESCRIPTION:
A mock corporate booking tool which can demonstrate the ability to place well targetted, contextual advertising. The demo will include parameters to adjust the values of the traveler and the trip, and view the resulting adjustments in the advertising targetting in real time.

SUMMARY OF THE INTERFACE:
1. Mock up of three screens with the corporate booking tool (Trip Review, Search, Other (TBD))
2. Panel to manipulate the parameters of the traveler
3. Panel to manipulate the parameters of the trip
4. Panel to show the search queries that reflect the resultant advertising
5. Tooltips to show the potential yield for a travel publisher (per ad)

PARAMETERS:
1. Traveler Profile:
    1. Age
    2. Gender
    3. Corporate Rank (Executive / Mid Level Sales)
2. Trip Context:
    1. Booked Segments (Air / Hotel / Car)
    2. Previously visited the city
    3. Number of travelers

SCENARIO 1: Executive with Air Segment Booked
- An executive is travel to NYC on business. Their flights are booked, but no other aspects of their trip.
- Show accommodation, car rental and entertainment advertising relevant to this traveler

SCENARIO 2: Executive with Air & Hotel Segments Booked
- The same executive is travel to NYC again on business. Their flights and hotel are booked, but no other aspects of their trip.
- Show car rental and entertainment advertising relevant to this traveler *

* Can we identify that the traveler does not want car rental if that's the case?

SCENARIO 3: Mid-level sales person with Air, Hotel & Car Segments are Booked
- A Mid-level sales person is traveling to NYC for a sales pitch with a prospect. Their flights, hotel and car rental are booked
- Show entertainment advertising relevant to this traveler

TO DO:
1. Select a location to sample
2. Assume there's an air segment
3. Create a sample of hotel advertisements
4. Create a sample of restaurant advertisements