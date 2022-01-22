# weather-api

Here's an example of a slightly less than simple version of an API server which uses OpenWeatherMaps API key written using Python.

the API key should be created from the openweathermap website - it's a free registration- no affliliation ;) 
and stored as an environment variable API_KEY using  export API_KEY=<your_api_key>

It has three endpoints:

* /
* /ping
* /weather

To run it, you can edit line 1 with the path of python3, or via the command line
`# python3 ./server.py` 
