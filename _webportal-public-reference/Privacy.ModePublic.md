---
title: Privacy.ModePublic

supported:
  - 3
  - 4
type: event
---
Event triggered when the Public privacy mode is selected.

### EXAMPLE

```javascript
try {
	// Privacy
	if ((typeof Privacy !== "undefined") && (typeof Privacy.addEventListener !== "undefined")) {
		Privacy.addEventListener("ModePublic", function(){
			alert("Public privacy mode is now active");
		});
	}
} catch(e) {
	DealWithPrivacyError(e);
}
```

*Appeared in Wave 4.1 - version 30.05.14.30*