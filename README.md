# HomeInventoryChecker
I am looking to develop a web application to check the current database of my my household in this repository. In this page, I wil describe the basic design of the application and workflow, which will help me devise a protype design, on which I will be working on to refine and finally develop the application.

**Input:** I would like to get the product IDs via the following methods:
1. Manual Entry (which is the most essential one)
2. Barcode and/or QR scanner

**Possible Implementation Logics:**
1. The product will be recognized via the input mechanisms mentioned earlier, an it'll get additional information from the public databases about it. Initially, this will be: full name, weight, serving size and calories per serving (this will be expanded later)
2. Once a product is entered, if it already exists in the inventory, it'll just add it. If not, then it will create an instance in the inventory database. The user will be notified about the existance of a product in the inventory if it's already available and confirmed if this product is been added.
3. The expiry date should be gathered from the product. We need a viable solution to achieve this.
4. User must be notified about the expiry date once that is approaching (2nd Phase)
5. The internal database must be categorized where each product is arranged in categories and sub-categories.

**Output:** User will see the whole available inventory in his/her dashboard, with all informtion being visible if s/he wants to see the details.
