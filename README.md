# Redirect Confirm
=========
Redirect Confirm Popup Message with Bootstrop 3

#Usage

```JS
$(document).ready(function() {
	jQuery(document.body).RedirectConfirm({
		selector: ".selector a",
		title: 'Exiting our website',
		message: 'You are now leaving our website. We are not responsible for any external Web sites or their content.',
		returnlbl: 'Continue',
		continuelbl: 'Return',
		targetUrl: '_blank'
	});
});
```

#Options
Option | Description
---|---
selector | Your `a` tag selector class
title | Popup modal title
message | Popup modal description
returnlbl | Redirect cancel button label
continuelbl | Redirect confirm button label
targetUrl | Url Target [Definition and Usage] (http://www.w3schools.com/tags/att_a_target.asp)