https://tejasg-007.github.io/electricitydemo.github.io/#/

Develop a pseudo FullStack application in any tech-stack which manages electricity bill record for a house
[Minimum Requirement] (entry level)
-CRUD App (Create,Read, Update, Delete)
-A GET request to the base URL should list a table with all previous months electricity bill record
- A GET request to /bill:id should list details of a particular record. This will be on click of the button from above table
-A GET request to laddBill should show a form for adding a new bill entry. The form should contain details such as bill date, paid date, unit consumed, amount etc.
-A POST request to / should submit the above form and add it to the database.
-A GET request to I:idledit should show a form which has prefilled details & it must be possible to change required Details.
-A PUT request to /:id/edit should submit the above form and change the appropriate details in the database.
-A DELETE request to /delete/:id should delete that particular record from the database.
-A Delete & Edit button should be there in /bil/:id
