## Updated file(s):
- Product__cs.json
- ProductController.cls
- productCard.html
- productCard.js
- productFilter.html
- productFilter.js
- getProducts.json
- Frame_Color__c.field-meta.xml
- ProductList.listView-meta.xml
- E_Bikes.site-meta.xml


## Task Completed 4/4:
I believe that I completed all 4 of the tasks to the best of what I interpreted from the assessment requirements description.

Task 1: 
- Updated the sample data to have default frame colors. Had to reinitiate data on Playground to have effect.
- Updated product filters LWC with a multi select section for frame colors that are found under the meta xml.
- Added logic to handle the event for color filter.

Task 2:
- Updated product filters LWC with a slider for page size up to 50 items per page, with a default of 9 items per page.
- Added logic to handle the event for page size filter.

Task 3:
- Updated the product Card LWC with accordion components for the header sections (Electric Componenets, Frame, and Brakes), defaulted to showing each expanded.
- Added logic to handle the event to collapse and expanded the accordion.

Task 4:
- Added the rest api site to CSP Trusted Sites within the Setup Settings.
- Added the rest api site to Remote Site Settings with the Setup Settings.
- Added chrome extension to handle allowing CORS: Access-Control-Allow-Origin.
- Added the rest api fetch call within the event handler that handles the product tile click.
- Within the rest api fetch call the information for current inventory and new restock date is collected.



## Things to improve or modify:
- Could have add more test cases for the new added filters and api call; not sure if it fitted in with the scope of this assessment.
- For task 1, I could have added dropdown menu for the color selection filter.
- For task 2, I could have added the page size filter within the product tile list LWC to have it more integrated with the results page.
