---
title: About
layout: about
permalink: /about.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/jumbotron.html objectid="/objects/newerbanner.jpg" heading="About this Collection" text= false %}

{% include feature/nav-menu.html sections="Staff;Acknowledgements;Metadata Standards" %}

## Staff

Ryan Hedrick is the sole staff involved in creating this CollectionBuilder site. Ryan is a second year MLS student at Indiana University Bloomington. Also, Ryan is an avid film buff, which is why this collection is based on items in his own personal movie collection. This CollectionBuilder site was built as part of a final project assignment for the Digital Libraries class at KU Bloomingotn.

## Acknowledgements

I would like to thank Professor John Walsh and Associate Instructor Alex Wingate for their continued assistance and availability when I needed help with setting up this collection. I would also like to thank Olivia Wikle and Devin Becker from the Univerity of Idaho and the CollectionBuilder team for speaking to our class earlier in the semester and making themselves available to answer any questions my classmates or I had regarding the use of their CollectionBuilder framework.

## Metadata Standards

For this collection 14 metadata fields were used to describe the objects included in this collection. Of the fields, four of them (objectid, filename, title, and format) are required CollectionBilder fields. Another three fields (date, description, and language) were taken directly from Dublin Core Elements. The remaining seven fields are custom fields that I created specifically for this collection. All seven of those fields can be mapped to Dublin Core.
### Metadata Elements
**ObjectID - required, 1 value allowed**

The Object ID serves as a unique identifying string of characters to identify each object in the collection. In order to keep things simple, the same formatting used for filename will be used for object ID, however, without the need for a file format.

Examples: goodfellas_1990, scottpilgrim_2010, starwars_1977

**Filename - required, 1 value allowed**

The filename is the name the object is saved under. Filenames will be formatted in a title_year format. Title will always be lower case with no spaces and the year will be formatted as YYYY. The title used for this name may be a shorter version of the full title. Also, the entire filename will include file format such as JPEG.

Examples: goodfellas_1990.jpg, scottpilgrim_2010.jpg, starwars_1977.jpg

**Format - required, 1 value allowed**

Format refers to the format of the file of each object being uploaded to the collection. According to CollectionBuilder documentation, “the input for this field should be structured according to MIME type standards, consisting of a type and a subtype concatenated with a slash (/) between them.”

Examples: image/jpeg

**Title - required, 1 or more value(s) allowed**

The title serves as the visible name of an object and will be written as the film’s proper name. The name of the film was taken as it appeared on the cover of the disc case. The title is also formatted as shown on the cover, with all proper grammar and spacing.

Examples: Goodfellas, Scott Pilgrim vs. the World, Star Wars: Episode IV – A New Hope

**Description - required**

The description element includes a short description of each film. The description was taken from the movie website IMDB.

**Director - required, 1 or more value(s) allowed**

Description: The director element includes the name of the director(s) that directed the film. This information will be taken from the credits of the film. The name of the director will be formatted with all proper grammar and spacing.

Examples: Martin Scorsese, Edgar Wright, George Lucas

**Top Actors - required, at most 3 values allowed**

The actors element will include the name of, at most, the top three billed actors. This information was taken from the film’s credits, or on the back of the DVD box. Actors’ names are formatted with all proper grammar and spacing. Values in this field will be separated with a “;”.

Examples: Robert De Niro, Michael Cera, Mark Hamill

**Genre - required, 1 or more value(s)**

The genre element serves as the field to categorize the primary genres of a film in the collection. The length of the movie was taken from the movie website IMDB. The genres are formatted with all proper grammar and spacing. If a film has more than one genre listed then it is separated with a “;”.

Examples: Crime; Drama, Action; Adventure; Fantasy, Action; Comedy

**Date - required, 1 value allowed**

The date element refers to the year of the film’s initial U.S. full theatrical release. This information was taken from the back of each disc cover. These dates will feature only the year and will follow the YYYY format.

Examples: 1990, 2010, 1977

**Runtime - required, 1 value allowed**

The runtime element will include the time length of the film displayed in hours and minutes. The length of the movie was taken from the movie website IMDB. The runtime element follows the h/m format.

Examples: 2h 25m, 1h 52m, 2h 1m

**Rating - required, 1 value allowed**

The rating element refers to the rating given to the movie by the Motion Pictures Association's Classification and Rating Administration. The rating of the movie was taken from the back of the disc cover.

Examples: R, PG-13, PG

**Subject - required, 1 value allowed**

The subject element serves as the field to categorize the video format of each disc. While some objects include multiple video formats in the disc box, only the primary format will be listed. The element is named subject because it is the name of the field required by CollectionBuilder. The proper names of each format will be formatted with all proper grammar and spacing.

Examples: Blu-Ray, DVD

**Language - required, 1 value allowed(s)**

The language element refers to the primary language that the film is formatted to. The language of a film in this collection will be determined by the language the film was originally filmed in. The values of the language element are formatted as abbreviations of each language based on Library of Congress standards.

Examples: eng, spa, ita
