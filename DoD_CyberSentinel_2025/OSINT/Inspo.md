Difficulty: Medium
Points: 200

Description:
We believe that the North Torbians are heavily influenced by North Korean developments and wish to match them. We have suspicions that Juche Jaguar will try to build out similar spaces to ones in these pictures. Can you find the coordinates of where these pictures were taken?
The flag is any valid decimal degree coordinate notation within a 500m radius of the building. The flag is in the following format: C1{XX.XXX,XX.XXX}
For example, the White House would be at decimal degree notion of 38.897, -77.036. The flag for the White House would be: C1{38.897,-77.036}
Note that this flag is a regex match for any valid coordinate within the 500m radius.


For this one, I had to find a specific location in pyongyang, North Korea, where a gaming center had been built.
I was only given two images by the challenge, one was from inside the building, and one was from the outside, supposedly nearby.
The image from the inside didn't have any windows in view, so I couldn't get anything from that.
The image from the outside didn't have the actual building in view, but nearby was an overpass connecting two tall buildings with a clock on either side.
This looked like a pretty major landmark, but any google searches with a description of this landmark gave no results.
Eventually I tried reverse-image-searching the photos on google, which led to some news articles covering the gaming center.
I found out that the center was built in the heart of the Hwasong district in Pyongyang, which thankfully Wikipedia had an article for, which showed the exact borders of the district.
The place looked like a complete ghost town on google maps, despite apparently having undergone a gigantic construction project recently, which included the construction of -
the gaming center i was looking for, as well as the overpass with the clocks.
In one of the news articles I found, there was a photo of the overpass from another angle with two distinct skyscrapers in the background.
Those skyscrapers were on the google maps sattelite images, and I was able to use them as a reference for where the clock overpass was.
After that, I used google maps to get the coordinates of a place where I roughly figured the overpass was, and after inputting the coordinates for the flag, I completed the challenge.

Note: After finding the coordinates, when I first input them as the flag, it was marked as incorrect. This was because I didn't notice I was pasting them in with an extra space.
I then spent at least 30 minutes second-guessing where I thought it was before I realized and removed the space.
