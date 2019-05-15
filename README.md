# InstaKilo

Learning Outcomes
can use a UICollectionView to display content in a scrolling grid
can successfully and properly manipulate static data
Goal
The world is once again craving yet another photo app to help them manage their photos! You're going to build one.

Requirements
User Stories
User should be able to view all the photos. 
As a 'InstaKilo' user 
I want to be able to brows through all my photos 
Because I want to know which photos I have access to in the app 

User should be able to view photos by category.
As a photo app user
I want all my photos to be grouped by location or subject
Because I want to easily see which photos are related to each other

Stretch User Stories
The app should look like a real photo album.
As a designer
I want the collection view to have a custom background
And I want each photo to have a more random layout
Because I want the photos to look more like they are in a real photo album

User should be able to delete photos.
As a photo app user
I want to be able to delete photos
Because I want to control which photos are in the app

User should be able to re order photos.
As a photo app user
I want to be able to re oder the photos
Because I want to control over the order in which I see the photos

User should be able to organize photos into piles.
As a photo app user
I want to be able to organize my photos into piles
Because I want more control over how my photos are organized in the app

Problem
Setup
Create a new iOS project, using the Single View template.

To get started, we will be adding our own images to the project instead of using the user's photo library.

Add 10 or more images to the xcassets folder in your project.

Remember to commit your changes to git incrementally and push your local commits to GitHub as often as possible.

User should be able to view all the photos
Display all your photographs using collection view cells. You will have to create a custom UICollectionViewCell class to display a photo in each cell.

User should be able to view photos by category
When the user opens the app, all the photographs should be initially grouped by subject.

Use collection view sections to group the photographs by subject. Use a supplementary view that's a label that displays the title of the section.

The user should be able to choose how photos are grouped.

Show a segmented control that allows the user to pick from sectioning the photos by subject or location.

Tip: You may want to embed your view controller in a Navigtion Controller so that you can add this segment control to the navigation bar.

Stretch Goals
The app should look like a real photo album
Add a decoration view to the page of floral motifs by subclassing the flow layout
Change the layout object to have custom attributes for each cell that makes it feel more like photos in an album: tilt each photo slightly and shift their positions randomly just a bit, etc
User should be able to delete photos
Add the ability to delete a photo if the user double-taps a photo
Modify the flow layout subclass to have an custom animation when an item is deleted so that the item appears to fall off the bottom of the screen
User should be able to re order photos
Use Apple's documentation on Supporting Drag and Drop in Collection Views to allow user's to re order their photos.
User should be able to organize photos into piles
Add a segmented control to allow swapping between different layouts
Add pinch gesture recognizer
Set up an indexPath in the custom layout to track which items should be animated
Set up multiple properties (e.g., pinch scale, pinch centre) in the custom layout subclass to track the difference and animate expanding accordingly
If you upscale image in each cell as user pinches out, you may need to swap between the original image and one with larger resolution to prevent pixelate as the cell grows
