Algorithm for setting up a site on CMS ModX Revolution 
for publishing materials with additional fields using the example of price and image

Step 1. Using the package manager, add the packages
getPage, getResources, pdoTools, WayFinder

Step 2. Set up the initial template using the sample  
https://github.com/ArtNazarov/modx-rev-tpls/blob/main/default-template-bootstrap5.html

Step 3. Create a template for the list of items
https://github.com/ArtNazarov/modx-rev-tpls/blob/main/template-items.html

Step 4. Create a chunk to display one list item
https://github.com/ArtNazarov/modx-rev-tpls/blob/main/chunk-resourceRowTpl.html

Step 5. Create the mygroup category

Step 6. Move resources to the mygroup group via "Resource Groups"

Step 7. Create pages and attach them to the mygroup category

Step 8. Create a chunk for the active menu item template
https://github.com/ArtNazarov/modx-rev-tpls/blob/main/wf_hereTpl.html

Step 9. Create a chunk for the external part of the menu
https://github.com/ArtNazarov/modx-rev-tpls/blob/main/wf_outerTpl.tpl

Step 10. Create a chunk for the active parent menu template
https://github.com/ArtNazarov/modx-rev-tpls/blob/main/wf_parentRowHereTpl.html

Step 11. Create a chunk for the parent menu item
https://github.com/ArtNazarov/modx-rev-tpls/blob/main/wf_parentRowTpl.html

Step 12. Create a chunk for a regular menu item
https://github.com/ArtNazarov/modx-rev-tpls/blob/main/wf_rowTpl.html

Step 13. Add TV fields myimage as an image and priceCurrent as a number Both fields should be in the mygroup category

Step 14. After adding new fields, open the resource pages and fill in the additional properties that appear
