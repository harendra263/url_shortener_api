## URL Shortener API


DECIDE what your app can do

| Endpoint            | 	    HTTP Verb	|    Request Body	 |       Action                                                          |
| -----------         |:----------------:   | :------------------:| :---------:|
|   /	              |       GET		    |                    | Returns a Hello, World! string                                        |
|   /url              |	      POST	        |  Your target URL	 | Shows the created url_key with additional info, including a secret_key|
|  /{url_key}         |	        GET		    |                    | Forwards to your target URL                                           |
| /admin/{secret_key} |	GET		            |                    | Shows administrative info about your shortened URL                    |
| /admin/{secret_key} |	DELETE	            | Your secret key	 |  Deletes your shortened URL                                           |




Note: Without an __init__.py file, you’d create not a regular package but a namespace package. A namespace package comes in handy when splitting the package over multiple directories, but you’re not splitting the package in this project. Check out Python import: Advanced Techniques and Tips to learn more about packages.



credit: https://realpython.com/build-a-python-url-shortener-with-fastapi/#step-2-set-up-your-python-url-shortener