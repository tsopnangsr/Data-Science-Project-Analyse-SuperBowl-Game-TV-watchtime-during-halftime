# Data-Science-Project-Analyse-SuperBowl-Game-TV-watchtime-during-halftime
In this project, we loaded, cleaned, then explored Super Bowl game, television, and halftime show data. We visualized the distributions of combined points, point differences, and halftime show performances using histograms. We used line plots to see how ad cost increases lagged behind viewership increases. And we discovered that blowouts do appear to lead to a drop in viewers.

## Introduction
Whether or not you like football, the Super Bowl is a spectacle. There's a little something for everyone at your Super Bowl party. Drama in the form of blowouts, comebacks, and controversy for the sports fan. There are the ridiculously expensive ads, some hilarious, others gut-wrenching, thought-provoking, and weird. The half-time shows with the biggest musicians in the world, sometimes riding giant mechanical tigers or leaping from the roof of the stadium. It's a show, baby. And in this notebook, we're going to find out how some of the elements of this show interact with each other. After exploring and cleaning our data a little, we're going to answer questions like:

* What are the most extreme game outcomes?
* How does the game affect television viewership?
* How have viewership, TV ratings, and ad cost evolved over time?
* Who are the most prolific musicians in terms of halftime show performances?

![Katy Perry performing at halftime of Super Bowl XLIX.](/images/left_shark.jpg)
Katy Perry performing at halftime of Super Bowl XLIX. Photo by Huntley Paton. Attribution-ShareAlike 2.0 Generic (CC BY-SA 2.0).

## Dataset
The dataset we'll use was scraped and polished from Wikipedia. It is made up of three CSV files, one with [game data](https://en.wikipedia.org/wiki/List_of_Super_Bowl_champions), one with [TV data](https://en.wikipedia.org/wiki/Super_Bowl_television_ratings), and one with [halftime musician data](https://en.wikipedia.org/wiki/List_of_Super_Bowl_halftime_shows) for all 52 Super Bowls through 2018. Let's take a look, using display() instead of print() since its output is much prettier in Jupyter Notebooks.
You can know more about the SCRAPPING METHOD we've used [HERE](https://en.wikipedia.org/wiki/Web_scraping) if you also want to create your own Dataset.

# See some of our Conclusions down here:

## Do blowouts translate to lost viewers?
The vast majority of Super Bowls are close games. Makes sense. Both teams are likely to be deserving if they've made it this far. The closest game ever was when the Buffalo Bills lost to the New York Giants by 1 point in 1991, which was best remembered for Scott Norwood's last-second missed field goal attempt that went wide right, kicking off four Bills Super Bowl losses in a row. Poor Scott. The biggest point discrepancy ever was 45 points (!) where Hall of Famer Joe Montana's led the San Francisco 49ers to victory in 1990, one year before the closest game ever.

I remember watching the Seahawks crush the Broncos by 35 points (43-8) in 2014, which was a boring experience in my opinion. The game was never really close. I'm pretty sure we changed the channel at the end of the third quarter. Let's combine our game data and TV to see if this is a universal phenomenon. Do large point differences translate to lost viewers? We can plot household share (average percentage of U.S. households with a TV in use that were watching for the entire broadcast) vs. point difference to find out.

![Do blowouts translate to lost viewers?](/images/blowouts.png)

## Viewership and the ad industry over time
Regardless of the score though, I bet most people stick it out for the halftime show, which is good news for the TV networks and advertisers. A 30-second spot costs a pretty $5 million now, but has it always been that way? And how have number of viewers and household ratings trended alongside ad cost? We can find out using line plots that share a "Super Bowl" x-axis.

![Viewership and the ad industry over time](/images/image_comparition.png)

## Conclusions
In this project, we loaded, cleaned, then explored Super Bowl game, television, and halftime show data. We visualized the distributions of combined points, point differences, and halftime show performances using histograms. We used line plots to see how ad cost increases lagged behind viewership increases. And we discovered that blowouts do appear to lead to a drop in viewers.

Sincererly, Romaric Tsopnang. Connect with me on LinkedIn: https://www.linkedin.com/in/tsopnangsr/
