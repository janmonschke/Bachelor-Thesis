### Quo vadis / upcoming features
The development of Salon should not stop after this thesis and there are various additional features planned for the future:

## Remix-me
The "Remix-me" feature would allow a user to clone an existing page from another user to then edit it as if it was one of his pages. These remixes would then get listed on the original page and a caption would get added to pages that are remixes so that the original authors would always be mentioned. This feature should be an optional feature for pages and should need to get activated in the page edit form for each page to preserve copyrights of the original content.
A scenario could be that Profs create pages to specific topics and then make an exercise in class that students should remix the current page and add their own ideas to the page. This raises the question whether it should be allowed to the remixer to delete images from the original author.
Overall this feature could boost interaction between users and could be an element that is fun to use.

## More Assets
Currently there is only one asset type that can get added to pages: the image. But the backend design allows to easily add other sorts of assets for example texts or sounds. Especially the combination of text assets and image assets could lead to a lot of interesting pages. Texts could link to other pages or they could serve as a description for images.

## Animations
To improve the user experience, more animations could get added to Salon. For example when navigation through the images of a page with the keys, the images could slide-in from the side instead of just suddenly appearing after a key has been pressed.
Or a more complex animation: When selecting a page on a user overview, all other images could fade out. After all other images have been faded out and the new data for the page overview has been fetched, the new images for the page are placed behind the current image. They would then simultaneously fade in and get smoothly moved to their positions while the cover image fades out.
An advantage that comes with this animation is that users are able to see where all the images are placed, even those that would not be visible from the beginning. But this animation could distract the user's attention from what is really important on each page: the images and their arrangement.
  
## Zoom
Pages with a lot of images tend to look cluttered and then images are often dragged out of the visible area of the canvas. Sometimes this leads to several images get hidden by accident so that users will not notice that there are more images on the page. A zoom feature that lets users zoom in and out of overview pages would help to give users an overview of pages with a lot of content and could also be another element for users to experiment with (e.g. by hiding images that can only be seen when a user completely zooms out of the page).

## Grid Generator
Sometimes it is not necessary to align images on a page in very creative way when a user only wants to upload the images and show them to someone else. Currently to align them properly in a grid a user has to manually drag the images around. The more images there are, the more time is needed to create a nice grid and very often images are not aligned 100% correct because it is hard to align everything manually. To allow the user to simply create grids that are perfectly aligned, a grid generator component could get added to Salon that is visible on overview pages. A user would only have to specify the amount of columns and the padding and the generator would then align the images automatically.

## search for titles
The search currently only works for tags but this is a functionality that is likely to get extended in the future to also support the search in page titles and image titles. This makes it possible to find pages directly and not just by searching for tags that images in a specific page may have been tagged with. Students could then name their pages according to the exercises of Profs so that Profs can find these pages easier. This also leads to a needed restructure of the search result page that then should also show resulting pages.