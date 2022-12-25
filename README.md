## URL Shortener API


DECIDE what your app can do

| Endpoint   | 	    HTTP Verb	|    Request Body	 |   Action  |
| ------------- |:-------------:| -----:|:-----------:| -------:|
|   /	     |       GET		|                    |      Returns a Hello, World! string |
|   /url     |	      POST	    |  Your target URL	 | Shows the created url_key with additional info, including a secret_key|
|   /{url_key}|	        GET		|                    |  Forwards to your target URL|
| /admin/{secret_key} |	GET		|                    | Shows administrative info about your shortened URL|
| /admin/{secret_key} |	DELETE	|   Your secret key	 |  Deletes your shortened URL |


credit: https://realpython.com/build-a-python-url-shortener-with-fastapi/#step-2-set-up-your-python-url-shortener