# THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS
## INTRODUCING HTML5 STORAGE:
 ### With web storage, web applications can store data locally within the user's browser.
 ### Before HTML5, application data had to be stored in cookies, included in every server request. Web storage is more  secure, and large amounts of data can be stored locally, without affecting website performance.
 ### Unlike cookies, the storage limit is far larger (at least 5MB) and information is never transferred to the server.
 ### Web storage is per origin (per domain and protocol). All pages, from one origin, can store and access the same data.
 ## USING HTML5 STORAGE:
 ### The local storage is a type of HTML5 offline storage that allows user string data to be saved synchronously in their browser. Information is kept in name and value pairs and not available between different browsers on the same device.
 ## STORAGEEVENT OBJECT
PROPERTY	|   TYPE	 |                 DESCRIPTION
--------    |  ------    |                --------------
key	string	|   the      |   named key that was added, removed, or modified
oldValue	|   any	     |   the previous value (now overwritten), or null if a new item was added
newValue	|   any	     |   the new value, or null if an item was removed
url*	    |  string	 |   the page which called a method that triggered this change

## WEB SQL DATABASE SUPPORT
IE |FIREFOX	| SAFARI |CHROME |OPERA |IPHONE	 |ANDROID
-- | -------| ------ | ----- |----- | ------ |-------
·  |  ·	    |  4.0+  | 4.0+	 | 10.5+|  3.0+  |	2.0+

>At time of writing, IndexedDB has only been implemented in a beta version of Firefox 4. (By contrast, Mozilla has stated that they will never implement Web SQL Database.) Google has stated that they are considering IndexedDB support for Chromium and Google Chrome. And even Microsoft has said that IndexedDB “is a great solution for the web.”

