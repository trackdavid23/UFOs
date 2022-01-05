# UFOs
### Creating a website using javascript to allow user to filter of UFO Sigthing.
Enhance our webpage with capability adding filters with multiple factors. D3 functionality makes an instance listener for multiple changes in our search, displaying needed datasets on the result table.
By creating more table filters, as well addition to the date filter you created in this module, you’ll add filters for the city, state, country, and shape, as shown in the following image:
![Screen Shot 2022-01-05 at 5 49 15 PM](https://user-images.githubusercontent.com/59430635/148300832-47785ccc-e7de-4210-a6b4-646837328696.png)

Using JavaScript, you’ll replace the handleClick() function in your app.js file with a new function that saves the element, value, and id of the filter that was changed. Then, you’ll create a new function to loop through the dataset and keep only the results that match the search criteria. The webpage will be updated with the search criteria after pressing "Enter".

The list element that creates the button is removed, and there are five list elements for filtering in the index.html file.
The event listener is modified to detect changes to each filter in the app.js file.

•The updateFilters() function saves the element, value, and the id of the filter that was changed.

•The filterTable() function loops through all of the filters and keeps any data that matches the filter values.

•The webpage filters the table correctly based on user input.

![Screen Shot 2022-01-05 at 6 01 38 PM](https://user-images.githubusercontent.com/59430635/148302078-f3266b0b-6a34-4f98-bc4d-1567281fa1b9.png)
In the end the site will look like this:

![Screen Shot 2022-01-05 at 6 06 01 PM](https://user-images.githubusercontent.com/59430635/148302455-e596d4ee-dace-474e-a4ca-8157f13e003c.png)
