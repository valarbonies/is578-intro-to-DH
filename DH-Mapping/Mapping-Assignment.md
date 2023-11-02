# Mapping

I did assignment one using a dataset I created by web scraping all the Airbnb rentals in Puerto Rico (I used a free Airbnb Scraper tool available through [Apify](https://apify.com/dtrungtin/airbnb-scraper)). I was born and raised in Puerto Rico and I really wanted to visualize one of the current problems and reasons for a lot of the displacement, gentrification, and homelessness that locals are experiencing back home. Here's a New York Times article from a friend on the subject: [The Rush for a Slice of Paradise in Puerto Rico](https://www.nytimes.com/2022/01/31/us/puerto-rico-gentrification.html)

For this assignment I used **kepler.gl** and **geojson.io**. 

Before I started mapping, I edited parts of the dataset (typos and repeated words) and eliminated some columns (stars, rating, name of host, guest capacity) I didn't need for the purpose of this assignment and then uploaded it to kepler.gl. With the dataset uploaded, I decided to first add a layer to represent all the rental locations as blue points in the map. 

![kepler gl_rentals_ss](https://github.com/valarbonies/is578-intro-to-DH/assets/109615094/90cb1d92-bd17-4b32-b0ca-d54aea7b0e3a)

When you click a point, a panel pops up and shows you the name of the rental (as was advertised on Airbnb), price per night, lat/lon, and name of town. 

![kepler gl_rentals_panels_ss](https://github.com/valarbonies/is578-intro-to-DH/assets/109615094/d22c4e14-a61d-47ea-8949-207c6aaac527)

I then wanted to see the regions with the most Airbnb rentals by adding a layer of clusters. 

![kepler gl_clustered_rentals_ss](https://github.com/valarbonies/is578-intro-to-DH/assets/109615094/190169e1-4935-4191-88e5-1e2a780df435)

When I activate both layers it looks like this:

![kepler gl_multilayer_ss](https://github.com/valarbonies/is578-intro-to-DH/assets/109615094/7579d4f2-e2c2-4dc1-b616-a4ba577d7b9a)

I uploaded the same dataset to geojson and the first thing I noticed was that it needed a while to process large datasets (my dataset is 4,165 rows long). Whereas kepler.gl took less than a minute to upload. Second, I found it hard to understand geojson's interface and nothing popped up when I opened it that signaled a tutorial or tour of the tool. I also wasn't sure how I could add different layers or even edit how geojson had understood my dataset when I uploaded it, which was by representing each rental location with icons. Below is a screenshot of it.

![geojson io_ss](https://github.com/valarbonies/is578-intro-to-DH/assets/109615094/09b8ec0e-0980-46f8-b93d-8916320df1e8)

Overall, I will definetely be using kepler.gl in the future as from my experience it was more intuitative to use. I also really like the aesthethic of it. 
