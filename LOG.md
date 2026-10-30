# Log

One entry for each recipe, selection or Track B model you train, newest at
the bottom. The numbers come from `experiments.csv`. "Why" and "what it means"
are in your own words: your agent asks you for them and does not make them up.
End the log with your plan for what to try next.

<!-- The form of an entry:

## <date> <tag> (Track A or B)
- changed: what is different from the run before
- why: your reason
- validation: 0.000 (before: 0.000)
- what it means: what you think the result says
-->

## STEP 1   — What helps distinguish cities

1. Busan
- Beaches, large bridges, mountains, tall buildings near the sea, and some traditional temples.
- Subway stations, some of them also show the station name, coastal trains, monorails, city streets, and Korean signs, typically with the word “부산”.
- People walking along the seaside, visitors enjoying beaches, and vendors selling things at local markets; some people also wear navy uniforms. 
Street food stalls, Korean ‘hotteok’, fresh seafood, and traditional food markets.

2. Seoul
- Grand traditional palaces, old city gates, traditional Korean houses (hanok), bridges over the Han River, modern buildings, peaceful parks, historical statues and artworks in the National Museum of Korea.
- City buses, subway stations and platforms, and Korean signs.
- People wearing traditional Korean hanbok at palaces, crowds walking through busy streets even at night, many people visiting popular shopping malls and shopping streets 
- Korean street food such as tteokbokki and gimbap, hot Korean stews, Korean barbecue, cold noodles, and traditional kimchi jars.

3. Osaka
- Modern high-rise buildings, traditional Japanese temples, old bridges. Some images also show parks, rivers, and city views from above.
- Trains, subway stations and platforms, railway tracks, diverse individual cars.
- Narrow but colorful shopping streets. with eye-catching Japanese signs.
- Many people go shopping, have meals at restaurants, walk through shopping streets, and visit local attractions.
- Small but cozy cafes, restaurants, Asian food shops, Japanese drinks, and food stalls in busy shopping areas.

4. Tokyo
- Tokyo Tower, Tokyo Skytree, Tokyo Station, traditional temples and shrine gates, bridges, and modern high-rise buildings. In some pictures, there are also firework displays. 
- Wide streets, many trains and railway tracks, elevated roads, large pedestrian crossings, and Japanese signs.
- Crowds crossing busy intersections, office workers commuting by train, young people wearing cosplay costumes or traditional Japanese clothes (yukata)
- Different Japanese dishes such as ramen, beef rice bowls, grilled eel rice, traditional side dishes, and small food shops.

5. Taipei
- Modern high-rise buildings, traditional temples, old buildings, rivers, green parks, and historical objects displayed in museums. Some images also show traditional Chinese-style buildings and decorations.
- City buses, many scooters on the streets, busy intersections, airplanes near the airport, and street signs written in Chinese.
- People attending classes and events, visitors exploring historical sites, and crowds walking through colorful and festive streets.
- Taiwanese street food, grilled meat, food stalls, night markets with bright signs and small shops.

## 2026-10-30 baseline (Track A)
- changed: nothing; the starter recipe as it came, with all the starter training
  photos, trained twice: seed 0 and seed 1
- why: the purpose of the baseline is to give me a starting point for comparing
  further experiments
- validation: 0.4896 (seed 0), 0.4922 (seed 1); before: none, this is the
  starter recipe
- what it means: the scores are close but they are not exactly the same, even
  though the recipe and training photos are the same. This shows that random
  factors can affect the results. When I test a new recipe, I should consider
  this variation before deciding whether the change improves the model.

  ## STEP 3: Two mistakes 
1. Similar urban environments
Many images show similar urban features such as vehicles, buses, trains, buildings, and other infrastructure. As all five cities are large urban areas, these features often look similar. As a result, the model may have difficulty distinguishing one city from another based only on their general urban environment.

2. Similar streets, shops, and signs
Many images contain shopping streets, local shops, restaurants, and street signs that look similar across different cities. The model may struggle to distinguish three languages, people, and cultural characteristics from these images.