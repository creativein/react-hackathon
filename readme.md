***Description of the project***

In a React.JS app with PouchDB, use the included back-end of PouchDB to enable unidirectional and bidirectional replication and sync between 2 or more PouchDBs. For the data, just generate a 5x5 table of random numbers. Use the native permissions capabilities of PouchDB and display those in the React app. Then display the following in the front-end graphically in React in a Handsontable.JS:

- Keep track of the user
- Display the audit table
- Display the revision history tree as a chronological list similar to github's commit history
- Clicking on the tree branches restores the PouchDB back to that point in history.
- Show diffs between different versions, using Couchdiff, or couch-db-compare
- Make sure the PouchDBs also can sync correctly with other PouchDBs, ensuring the above functions work also with this.

Example starting repo: https://blog.logrocket.com/building-an-offline-first-app-with-react-and-rxdb-e97a1fa64356