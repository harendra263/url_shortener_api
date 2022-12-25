## URL Shortener API


DECIDE what your app can do

Endpoint    	    HTTP Verb	    Request Body	    Action  <br>
/	                GET		                            Returns a Hello, World! string <br>
/url	            POST	        Your target URL	    Shows the created url_key with additional info, including a secret_key <br>
/{url_key}	        GET		                            Forwards to your target URL <br>
/admin/{secret_key}	GET		                            Shows administrative info about your shortened URL <br>
/admin/{secret_key}	DELETE	        Your secret key	     Deletes your shortened URL <br>


credit: https://realpython.com/build-a-python-url-shortener-with-fastapi/#step-2-set-up-your-python-url-shortener