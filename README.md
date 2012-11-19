niagara
=======

Niagara is a very basic HTTP tool, written to find the maximum throughput a computer can physically produce, in terms of requests per second.

Everything runs in one thread, for maximum performance. Only plain HTTP is supported.

````bash
$ niagara --help 

Usage: niagara [OPTIONS...] URL
   OPTIONS
      -n, --requests=N       Total number of requests
      -c, --concurrency=N    Number of concurrent connections
      -H, --header           Add a HTTP header
      -h, --help             Display this help and exit
````

Send 1M requests to your localhost web server, adding a custom header:

````bash
$ niagara -n 1000000 -c 1000 -H "Connection: keep-alive" http://localhost/path
````