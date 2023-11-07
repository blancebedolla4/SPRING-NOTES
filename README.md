# SPRING-NOTES
HTTP 200 OK //HTTP status "200 OK" = processed sucessfully "OK" status = request processed w/out errors
Allow: GET //HTTP response header  specifies methods that are allowed for request recourse "GET" method is allowed for this
Content-Type: application/json //another response header "Content-Type:" specifies the format of the data in response body
Vary: Accept //The "Vary" header is used to indicate that the response can vary based on the "Accept" header in the request.
            //In other words, the response format might depend on what the client specified in the "Accept" header of its request.
            //For example, if the client requested JSON, the response would be in JSON format.

[
    {
        "created_on": "2023-11-06T20:02:54.821853Z",
        "unix_time": "1699300974.0",
        "expiration_time_unix": "1699301007.0",
        "ticker": {
            "ask": "473.03689688",
            "bid": "472.58979206"
        },
        "market": {
            "name": "n.exchange",
            "code": "nex"
        },
        "rate": "472.813344469223985",
        "allowed_historic_price_variance": true,
        "allowed_historic_price_age": true
    }
]

The data enclosed in square brackets [] is a JSON array, which can contain one or more JSON objects.
Inside the array, there is a single JSON object with several key-value pairs.
Key-value pairs are separated by colons :. For example, "created_on": "2023-11-06T20:02:54.821853Z" 
pairs a key ("created_on") with a value ("2023-11-06T20:02:54.821853Z").
Some values are strings, some are numbers, and one is a boolean (true or false).
Nested objects are used, such as "ticker" and "market," which have their own key-value pairs.
other notes
Beans in Spring are Java objects managed by the Spring container. They are configured, created, and injected with dependencies as per the Spring configuration, promoting modularity, maintainability, and testability in your application.
