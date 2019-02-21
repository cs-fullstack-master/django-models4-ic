# Django Models and Foreign keys

# django-models4-ic

## Lecture:

### Exercise 1
Create a model called ```Reporter``` with ```reporter_first_name```, ```reporter_last_name```, and ```reporter_email```.

Create a second model called ```Article``` with ```article_name```, ```article_pubdate```, and ```article_reporter``` that is a ForeignKey that references ```Reporter``` (deleting a Reporter SHOULD delete all of their articles)

Add 3 reporters using the Django Admin console

Add 6 made up articles using the Django Admin console

Assign 2 of the made up articles to each reporter using the Django Admin console

Add an endpoint ```reporters/``` that will list all Reporters and their Articles

Add an endpoint ```delete/``` that will delete the last Reporter and all of their their Articles

Confirm deletion by using the ```reporters/``` endpoint


## In Class

### Exercise 1
Create a model called ```Band``` with ```band_name``` and ```band_genre```.

Create a model called ```Album``` with ```album_name```, ```album_release_date```. and ```album_band``` that is a ForeignKey that references ```Band``` (deleting a Band SHOULD delete corresponding albums)

Add 2 bands using the Django Admin console.

Add at least 2 albums of your choosing to each band using the Django Admin console

Add an endpoint ```bands/``` that will list all Bands and their Albums

Add an endpoint ```delete/``` that will delete the last Band and all of their their Albums

Add an endpoint ```updatedate/``` that will update the ```album_release_date``` of the first ```Album``` for all bands to ```1999```

Confirm deletion/update by using the ```bands/``` endpoint




