# tributary


* A /record endpoint, which will record a new engine temperature reading to the database. The embedded sensors will post new data to this endpoint many times a second, giving the illusion of a continuous stream of data.
  
* A /collect endpoint, which will collect the most current engine temperature from the database and calculate an average. The mobile application will repeatedly post requests to this endpoint to collect up-to-date data.
