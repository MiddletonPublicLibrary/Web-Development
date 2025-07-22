# Into to Web Development
### An Introduction to HTML, CSS, and Github

## Adding your page to pages.json
> [!IMPORTANT]  
> You need to add your site to pages.json for the site to show up on the main site.
- Add The Following Line To The Bottom of pages.json right above the line with the ]
```
  {
    "name": "Site Name",
    "author": "Your Name",
    "file": "yourfolder/yourfile.html"
  },
```
## Making the site accessible
> [!NOTE]  
> You do not need to re run the command every time you make a change
- Open A Terminal
- Run The Following Commmand
```
python -m http.server 8000
```
- Open The Ports Tab
- Open the site from the list
