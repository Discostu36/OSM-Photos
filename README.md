# OSM Photos
Note: This project is still in its conceptional stage. **There is no app that you can use yet.** I am looking forward to your feedback and ideas (see below). 

## What is OSM Photos

### A photo viewer
OSM Photos is an app to view photos from [Wikimedia Commons](https://commons.m.wikimedia.org/) on a map. Instead of showing photos as pins or thumbnails at the location where the photo was taken, it highlights the objects (e.g. buildings, monuments) that are shown on the photo. Technically speaking, the app highlights all objects that have a `wikimedia_commons` tag in the [OpenStreetMap](https://github.com/openstreetmap) database. When selecting the object, the photo is shown or, in case of a linked Commons category, a gallery of all photos of the object are shown.

### A photo uploader
The other purpose of the app is to make it easier to upload photos of buildings, monuments etc. to Wikimedia Commons and link them to the corresponding objects in the OpenStreetMap database.

### Why do I need a new app for that?

#### Viewing photos of OSM objects
At the moment the only OpenStreetMap app with the feature to show photos of objects (that I know of) is [Osmand](https://github.com/osmandapp/OsmAnd). But it only shows photos of objects that are Points of Interest, no photos for unnamed buildings, streets, trees etc. It is also not possible to filter objects to only show those that have an image.

#### Uploading photos of OSM objects
At the moment finding objects that need photos, take and upload them to Commons and link them to OSM is a complicated process with at least two apps involved:
1. Use an OSM app, inspect the object to see if it already has an `wikimedia_commons` tag.
2. If not, open [Commons app](https://github.com/commons-app/apps-android-commons), take a photo, add descriptions, find and add fitting categories, upload. 
3. Copy file name.
4. Open an OSM editor, add the file name as `wikimedia_commons` tag. Upload.

With this the OSM Photos app, the workflow will be much more streamlined:
1. A map will show you at a glance which objects already have `wikimedia_commons` tags and which don't.
2. Select an object that needs a photo, press a button and upload a photo. 

You are done. The app will automatically add fitting descriptions  and categories to the Commons page of the file. It will then add the `wikimedia_commons` tag to the OSM object and upload that change to the OSM database.

## How can I help?
As this project is still in its conceptual stage, I need help in the following areas:

### Programming
I don't need pull requests yet, but if you have ideas how the app could best do what it should do, any help would be appreciated. Especially people familiar with Commons API and OSM API would be a big help.

### UX and features
If you have ideas how the app should behave to be as helpful and easy to use as possible for Wikimedia and OSM contributers, please contribute your ideas. Feature requests are also welcome.

### Design
If you are a designer and have ideas how this app could be designed, I would be grateful for your ideas. The difficult task is that this app is intended for Wikimedia and OpenStreetMap contributers, so the app should, if possible, have a design where both of these user groups can feel at home.
