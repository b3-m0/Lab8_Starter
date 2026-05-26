# Lab8-Starter

How are graceful degradation and service workers related?  
**Answer:** Graceful degradation and service workers are related in that service workers allow web applications to degrade gracefully when a user has a poor or nonexistent network connection. Instead of completely breaking when offline, an app with a service worker can still servce cached HTML, CSS, JS, images, and data from the browser's cache. This means users with slow or no network still get a functional experience, just without the latest network resources. The app degrades to its cached state rather than failing entirely. So service workers are essentially a tool that enables graceful degradation at the network level.
