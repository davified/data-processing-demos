# Data processing demos

For our intro/demo of various data processing tools, we can use the classic Hello World of big data processing - word count. We can use the Yelp reviews dataset (3.8 GB).

## Task

Do a word count on the yelp reviews dataset.

## Data

To get the data:
```
curl <url>
tar -xvf 
```

The data is in json format and here are 2 sample data points:
```
{"review_id":"VfBHSwC5Vz_pbFluy07i9Q","user_id":"cjpdDjZyprfyDG3RlkVG3w","business_id":"uYHaNptLzDLoV_JZ_MuzUA","stars":5,"date":"2016-07-12","text":"My girlfriend and I stayed here for 3 nights and loved it. The location of this hotel and very decent price makes this an amazing deal. When you walk out the front door Scott Monument and Princes street are right in front of you, Edinburgh Castle and the Royal Mile is a 2 minute walk via a close right around the corner, and there are so many hidden gems nearby including Calton Hill and the newly opened Arches that made this location incredible.\n\nThe hotel itself was also very nice with a reasonably priced bar, very considerate staff, and small but comfortable rooms with excellent bathrooms and showers. Only two minor complaints are no telephones in room for room service (not a huge deal for us) and no AC in the room, but they have huge windows which can be fully opened. The staff were incredible though, letting us borrow umbrellas for the rain, giving us maps and directions, and also when we had lost our only UK adapter for charging our phones gave us a very fancy one for free.\n\nI would highly recommend this hotel to friends, and when I return to Edinburgh (which I most definitely will) I will be staying here without any hesitation.","useful":0,"funny":0,"cool":0}
{"review_id":"3zRpneRKDsOPq92tq7ybAA","user_id":"bjTcT8Ty4cJZhEOEo01FGA","business_id":"uYHaNptLzDLoV_JZ_MuzUA","stars":3,"date":"2016-10-02","text":"If you need an inexpensive place to stay for a night or two then you may consider this place but for a longer stay I'd recommend somewhere with better amenities. \n\nPros:\nGreat location- you're right by the train station, central location to get to old town and new town, and right by sight seeing his tours. Food, bars, and shopping all within walking distance. Location, location, location.\nVery clean and very good maid service\n\nCons:\nTiny rooms \nUncomfortable bed \nAbsolutely no amenities \nNo phone in room \nNo wardrobe \n\nWas given a lot of attitude about me and my husband sharing a room which was quite strange and we were charged 15 pounds more for double occupancy not sure why that matters I felt like it was a money grab. It was just handled in a kind of odd manner to me... \n\nIf you book this hotel all you get is a bed, desk, and a bathroom. It isn't awful but know what you're getting into.","useful":0,"funny":0,"cool":0}
```

### Other datasets

Here are some other large datasets for your/our future practice:

- http://storage.googleapis.com/books/ngrams/books/datasetsv2.html
- https://github.com/logpai/loghub
- http://snap.stanford.edu/data/
- https://aws.amazon.com/public-datasets/
- https://archive.org/download/stackexchange
