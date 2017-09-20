# AroundUS

<br>Around:  Geo-Index Based Social Network</br>
<br>Developed an iOS app for users to post events and updates (description, geo-location, etc.)</br>
<br>Built a scalable web service in Go to handle posts and deployed to Google Cloud (GAE flex) for better scaling</br>
<br>Utilized ElasticSearch (GCE) to provide geo-location based search functions such that users can search nearby posts within a distance (e.g. 200km)</br>
<br>Used Google Dataflow to implement a daily dump of posts to BigQuery table for offline analysis</br>
<br>Aggregated the data at the post level and user level to improve the keyword based spam detection (BigQuery)</br>


