trump-tweets
============

The [donald-streaming.json](donald-streaming.json) file contains the JSON of Trump's tweets
as they were originally received through the geotagged tweet stream or the user stream.
Many of the tweets from the user stream were retweets or quoted tweets, so the metadata may
be different than it would have been at the time of the original posting.

The [html](html) directory contains files by year or month saved from the search interface
on the Twitter web site.

The [ids](ids) file is a list of tweet URLs taken from the HTML.

The [lookup.json](lookup.json) file is the tweet JSON of those IDs, retrieved using the
statuses/lookup API. This adds the time stamps and user-agent information that are not
shown in the HTML.
