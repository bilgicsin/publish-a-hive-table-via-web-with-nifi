# publish-a-hive-table-via-web-with-nifi
A simple web service example on NiFi. The flow consumes the request with a parameter over HTTP and returns a hive table query result which 
runs dynamically on parameter. On this case, web service consumes a user id and returns the user's info. On this senario a complex hive query
has been used and it is slow little but a hive table with single where condition will response much more faster.
