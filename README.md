# blackthorn-css
CAI Repository to server injection CSS for Salesforce Blackthorn events.


# Using custom CSS with Blackthorn
- Blackthorn event allow for extenal CSS injection through a custom URL. 
- We store this css in GitHub (`academic-innocation/blackthorn-css`)
- The default css, which is applied to everything in our Blackthorn instance is `EventBuilder__injection.css`

- Create a separate file by duplicating the original and uploading it to github with a unique name
- Use this unique name for an individual event to override the global css injection. 


## Expose the CSS vis Github Pages
Option 1: Use GitHub Pages (Recommended Native GitHub Method)
If your repository is Public, you can enable GitHub Pages. GitHub Pages automatically serves static .css files with the correct text/css MIME type.

### GitHub Settings:
1. In GitHub, open your repository (academic-innovation/blackthorn-css).
2. Go to Settings (top navigation tab).
3. In the left sidebar under Code and automation, click Pages.
4. Under Build and deployment > Source, select Deploy from a branch.
5. Select the main branch and leave the folder set to /(root).
6. Click Save.