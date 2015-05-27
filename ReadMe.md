R package for Bit.ly & Bitly.com & j.mp and other custom domains
============
Licensed under [MIT](http://en.wikipedia.org/wiki/MIT_License)

### What is/not implemented:

<http://dev.bitly.com/user_info.html>  | Implemented Yes/No
------------- | -------------
/v3/oauth/app  | (**NOT**, see below)
/v3/user/info  | Yes
/v3/user/link_history | Yes
/v3/user/network_history  | (**NOT**)
/v3/user/tracking_domain_list  | Yes

-------------------------

<http://dev.bitly.com/link_metrics.html>  | Implemented Yes/No
------------- | -------------
/v3/link/clicks  | Yes
/v3/link/countries  | Yes
/v3/link/encoders  | (**NOT**)
/v3/link/encoders_by_count  | (**NOT**)
/v3/link/encoders_count  | Yes
/v3/link/referrers  | (**NOT**)
/v3/link/referrers_by_domain  | (**NOT**)
/v3/link/referring_domains  | Yes
    
    
sadasfdsafsdgsfgbser


<http://dev.bitly.com/user_metrics.html> | Implemented Yes/No
    + /v3/user/clicks
    + /v3/user/countries
    
- <http://dev.bitly.com/organization_metrics.html>
    +
    
- <http://dev.bitly.com/links.html>
    + None endpoints are implemented here. 
    
- At the moment **no OAuth support** -> only basic [HTTP Basic Authentication Flow](http://dev.bitly.com/authentication.html#basicauth), which requires `Generic Access Token` from <https://bitly.com/a/oauth_apps>

- Additionally, only a **small subset of input paramaters** has been implemented. 

### How to Contribute

- Fork the repository
- Create and switch to a new branch `git checkout -b [name_of_your_new_branch]`
- Do the changes (i.e. edit files)
- Push remote branch to your github `git remote add [name_of_your_remote]` & `git push origin [name_of_your_remote]`
- Create a new pull request (to my `master` branch)

Want a direct push access? No problem, just let me know.

### Special Thanks to:

- Myself ([@dmpe](https://www.github.com/dmpe)) :yum:
- Somewhat (well, quite a lot) inspired by [Quandl Api R](https://github.com/quandl/R-package/)








