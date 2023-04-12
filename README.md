# Lost domain access - using a local JSON file for data

Due to the loss of our domain and access to our Wordpress site, we are no longer able to fetch data from the server directly. To work around this issue, we have created a local JSON file with the necessary data and are using that in our application.

The original code that fetches data from the server is still present in our JavaScript file, but it is now commented out since it is no longer in use.

To access the data, we are using the fetch() function to retrieve the data from the local JSON file. Once we have the data, we pass it to the appropriate functions in our application.

While this is not an ideal solution, it allows us to show our project without access to our original server.
