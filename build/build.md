# Site Build Scripting/Support

## Plan

- Scan root folder for directories not names "build"  
*I hate exceptions, but this seems unavoidable*
- Create ToC
- For each project directory
  - Parse markdown into input for page template(s)
  - Add to ToC
  - Output formatted HTML > ./site/projects/name.html
  - Output and supporting components
- Fixup ToC references
- Ouput formatted HTML for ToC > ./site/toc.html
