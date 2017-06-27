# sentry-disable-registration
Sentry - Disable user registration

[The official sentry docker image](https://hub.docker.com/_/sentry/) allows user registration per default. 
This allows access to logs containing confidential information.


[How I found your sentry instance and how to disable user registration](https://julian-uphoff.de/2017/06/24/how-i-found-your-sentry-instance-and-how-to-disable-user-registration/)


**Update 24/6/17 12:50Z:** Pull request started in [getsentry/sentry](https://github.com/getsentry/sentry/pull/5328#issuecomment-310836076) mentioning an issue by @alexandervlpl:

 > last night thousands of people received letters from a script that checked the availability of ALL data on their Sentry servers, because they forgot to turn off the registration, or did not know that it was turned on by default at all

**Update 27/6/17 06:40Z:** Registration moved behind option in the Sentry menu as of [getsentry/sentry#5620](https://github.com/getsentry/sentry/pull/5620).
