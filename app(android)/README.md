# Photo Library (Mobile)
Welcome to my mobile app guide. All the features are listed below. Feel free to roam around!

*[shortcut to the source code](./app/src/main/java/com/example/android/)*

**NOTE:**  
*As of now, this application is only available for android devices.*
![Alt text](./guides/android.png?raw=true "Logo")

## Overview
Photo Library gives you the power to create and manage albums directly from images stored on your device. You can move and copy photos between your albums. You can tag the people and locations in your photos. You can even view your collection with a built-in slideshow. This mobile version even lets you search for photos by their tags. 

Unlike the desktop application, the mobile version only supports a single user. This was a deliberate design decision. 

<!---
cut frames of gifs
-->

## Implementation
This application was written in java using [Android Studio](https://developer.android.com/studio)

## Data Management
Data persistence is achieved through [shared preferences](https://docs.oracle.com/javase/tutorial/jndi/objects/serial.html).

Photos are stored as [bitmaps](https://developer.android.com/reference/android/graphics/Bitmap).

## Albums
Click open, and let the adventure begin! You can easily add, delete or rename albums. 

<!---
![Alt text](./guides/album.gif?raw=true "Album")
<img src="./guides/album.gif" width="800" height="500"/>
-->
<img src="./guides/albumA.gif" width="400" height="800"/>

### Open
Opening an album allows you to select individual photos.

#### Add
Add a photo to the open album from your computer.

<!---
![Alt text](./guides/add.gif?raw=true "Add")
-->
<img src="./guides/addA.gif" width="400" height="800"/>

#### Move
Move a photo from the open album to another album.

<!---
![Alt text](./guides/move.gif?raw=true "Move")
-->
<img src="./guides/moveA.gif" width="400" height="800"/>


#### Delete
Delete a photo in the open album.

<!---
![Alt text](./guides/delete.gif?raw=true "Delete")
-->
<img src="./guides/deleteA.gif" width="400" height="800"/>


## Display
After opening an album and selecting a photo, you can display that photo and navigate through the entire album in a slideshow.

<!---
![Alt text](./guides/display.gif?raw=true "Display")
-->
<img src="./guides/displayA.gif" width="400" height="800"/>


### Tag
Tag your photos by people and location. 

<!---
![Alt text](./guides/tag.gif?raw=true "Tag")
-->
<img src="./guides/tagA.gif" width="400" height="800"/>


## Search
Search allows you to sort photos by people or location tags. 
<!---
![Alt text](./guides/search.gif?raw=true "Search")
<img src="./guides/search.gif" width="800" height="500"/>
-->

<img src="./guides/searchA.gif" width="400" height="800"/>

Turn on "*context search*" to return similar matches!

<img src="./guides/contextA.gif" width="400" height="800"/>

# Credits

![Alt text](./guides/about.png?raw=true "About")




