# unbundl Assignment

## Task 1

### Deployed: https://unbundl-assignment.vercel.app/

- Instead of hardcoding the product cards through HTML, productList are mapped through JavaScript.
- Use of Session Storage for storing the custom pack (collection) data
- Two pages ProductPage and CollectionPage with common Navigation bar at top
- Navigation bar is in module format so that it can be reused
- Logic for abstaining from multiple selection of same product, will alert that product is already added
- Maximum 8 chocolates can be added to the custom pack
- Quantity of custom pack is shown on the bag icon of Navbar, it will increase dynamically as the items are getting added
- Total Price of the collection calculated simultaneously
- Delete functionality on the CollectionPage for removing the item
- Removing of item will update the Total price as well

## Task 2

### Deployed: https://unbundl-assignment-oyoz.vercel.app/

- Navbar is made responsive by added hamburger menu for smaller screen
- First Single Picture Carousel feature is build using the list of array of images and setTimeInterval webAPI
- Change of different set of Images for First Carousal is achieved by putting the carousal logic in function and providing images through function argument.
- Resize EventListener is used for listen  for screen size
- Second Carousal with three products together is achieved through similar manner
- The Images and it's description on the side is achieved though use of grid-area property
- Responsiveness of the grid-layout is achieved using grid-area property itself