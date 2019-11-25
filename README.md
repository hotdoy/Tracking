# Tracking
Track multiple websites through a single GA account.

* Host ```index``` somewhere. 
* Add tracking.js to a project (make sure to replace UA-71334388-4 with your own ID)
* Add ```<div hidden id="tracking" data-ref="https://tracking.hotdoy.org/?ref={{ base_url_absolute }}"></div>``` at the end of the body of said project
* Replace ```https://tracking.hotdoy.org/``` in the step above with your own tracking URL.
