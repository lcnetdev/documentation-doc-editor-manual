# Doc Editor Manual



### About the Doc Editor system:

- A Manual is a collection of markdown files, directories and media files.
- Each manual exists as those files on the server and as version controlled files in a Git repository.
- The server renders the Markdown file into the web site and can build a PDF based on the same files.
- Each manual has two interfaces the "View" and the "Edit" 
  - The View interface is how users of the manual will interact with it, the rendered form
  - The password protected Edit view is how the manual editors will change and update the manual
- The system can support multiple manuals, meaning multiple collection of files stored in a git repo.

### Edit Workflow

1. The editor modifies or creates a file, including changing the markdown, adding new images, deleting files, etc.
2. The system changes the files on the server.
3. The system Git commits the files to the remote Git repository.
4. The system rebuilds the PDF document based on the order of links in the index.md file
5. The viewer will see the rendered markdown files as HTML when visiting the manual site.

### Features

Both the View and Edit mode of the tool has a number of features.


