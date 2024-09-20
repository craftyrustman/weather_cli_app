This is a simple weather app that gives you the weather reading for a particular city, it works on the CLI
I fetched data from openweatherapi, the free version
I used reqwest crate, to help with data fetching, serde crate for serialization and deserialization of data fetched from openweatherapi,
serde_json to convert the fetched data to json
I used colored crate to give colour to the weather results

There are two main fucntions here(three if you include the main one), one for getting the data and the other for displaying data
