Issue1: permanent redirects causing the url to not redirect to another domain if changed in config file
Solution: clear redirection cache and change redirect method to temporary

Issue2: redirect from a webpage of a website
solution: using regex "^/subdomain$" where "^" defines start of domain "/" defines subdomain "$" defines end of subdomain