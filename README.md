# Node.js Notes App

A 'yargs' interactive command line note app

## How to execute

```
node app.js --help
app.js [command]

Commands:
  app.js add     Add a new note
  app.js remove  Remove an existing note
  app.js list    List all notes
  app.js read    Read an existing note

Options:
  --help     Show help                                                 
  --version  Show version number                                      
```

Example:
```
node app.js add --help
node app.js add --title="Shopping list" --body="Buy bananas and strawberries"
```

## How to debug

1. Add the word `debugger` on the line above you wan to debug.
2. Execute the following command:
```
node inspect app.js add --title="Shopping list" --body="Buy bananas and strawberries"
```
3. Open the Chrome browser and type `chrome://inspect/devices`. It only works with Chrome.
4. Click inspect on relevant Node.js device 
