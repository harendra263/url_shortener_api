## URL Shortener API


DECIDE what your app can do

endpoint    HTTP verb   Request Body        Action
/           GET                             Returns a Hello, World String!!
/url        POST        Your target URL     Shows the created url_key with additional info,including a secret key
/{url_key}  GET                             Forward to your target url
