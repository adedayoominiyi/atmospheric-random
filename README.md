# atmospheric-random
Demo Java Tutorial on how to creat a true random number via random.org which use atmospheric noise as its source!

This demo supports the Blog Post "Generating a Random Number in Java From Atmospheric Noise" at mvpjava.com

You will have to get your own API key from random.org (free) and include it in the application.properties file as the 'apiKey'
If you do not, you will be using an expired key and you'll get the following error message ...

  .   ____          _            __ _ _
 /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
 \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
  '  |____| .__|_| |_|_| |_\__, | / / / /
 =========|_|==============|___/=/_/_/_/
[32m :: Spring Boot :: [39m      [2m (v2.1.3.RELEASE)[0;39m

==========================================
{
  "jsonrpc" : "2.0;",
  "method" : "generateIntegers",
  "id" : 0,
  "params" : {
    "apiKey" : "b5fa0720-e15b-477d-a875-fdaef6784471",
    "n" : 1,
    "min" : 1,
    "max" : 1000,
    "replacement" : true,
    "base" : 10
  }
}
{
  "jsonrpc" : "2.0",
  "result" : null,
  "id" : 0,
  "error" : {
    "code" : 401,
    "message" : "The API key you specified is not running",
    "data" : null
  }
}
!!!! An error occurred null ... returning an empty value !!!!
