msm - micro service manager

msm is a tool that listens to an url and depending on the arguments of that url
starts a request to certain micro services. 

	Example:
		if I call the adress *foobar.org/isOnline* msm, which listens at
		*foobar.org* checks if there is a service called _isOnline_ and triggers
		this. If there is no such service an 404 error is returned

