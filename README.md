---

TurboWarp IndexedDB Extension

This extension enables TurboWarp projects to utilize the browser's IndexedDB API, allowing for the storage, retrieval, and management of structured data directly within the browser.  By leveraging IndexedDB, your projects can handle larger and more complex datasets beyond the capabilities of traditional local storage. 


---

Features

Structured Data Storage: Store complex data structures like objects and arrays persistently.

Asynchronous Operations: Perform non-blocking read/write operations to maintain project performance.

Namespace Support: Organize data using namespaces to prevent key collisions between different projects or components. 



---

Usage Instructions

1. Loading the Extension:

Download the extension on http://pstorage.kenzieshane.my.id/indexeddb.js

Go open the Turbowarp Editor and or Open your Turbowarp project, click the add an extension button --> custom extensions --> add by files, then import the extension that you've just downloaded. I mean, copy and pasting the contents of the file also works

Check the box labeled "Run extension without sandbox" to grant necessary permissions. 


Note: Unsandboxed extensions have access to broader browser APIs, including IndexedDB. Ensure you trust the source before enabling this option.


2. Available Blocks:

Set Namespace [namespace]

Set Key [key] to [value]

Get Key [key]

Delete Key [key]

Clear All Keys 


These blocks allow you to interact with the IndexedDB by setting and retrieving values, organizing data under specific namespaces, and managing stored entries.




---
Example Usage

To store a player's score: 

Set Namespace [MyGame]
Set Key [PlayerScore] to [1500]



To retrieve the stored score: 

Set Namespace [MyGame]
Get Key [PlayerScore]




---

Important Notes

Unsandboxed Mode: This extension requires unsandboxed mode to access IndexedDB.  Only load extensions from trusted sources to avoid security risks.  

Browser Compatibility: IndexedDB is supported in most modern browsers.  Ensure your browser is up-to-date for optimal performance. 

Data Persistence: Data stored using IndexedDB persists across sessions but is specific to the browser and device. 



---

Additional Resources

TurboWarp Custom Extensions Documentation

TurboWarp Unsandboxed Extensions Guide



---

By integrating this extension, you can enhance your TurboWarp projects with robust data storage capabilities, enabling more complex and feature-rich applications. 

---

