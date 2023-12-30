# PhotoLibraryTools
Tools to sort, organise and fix a photo library.

### Image Date Fixer

Have a collection of images with incorrect dates? Or, maybe your entire photo library? Run this script to set the date in the image filename to the date modified, keeping your photo viewing software happy!


### Photo Library Organiser
Have a mess of folders with your photos and videos in? Or, perhaps one folder with all of your photos and videos in? Sort them into organised folders with this script!

### Basic Settings and Uses

Run the `libraryOrganiser.py` script to sort your library into subfolders by date modified, in the form shown below:<br>
`2023/2023-12/img.jpg`, where `img.jpg` represents an image with date modified of 21st Dec 2023.

By default, the script will create a new `Photo Library` directory, and move the organised photos into there. By default, the old copies of photos in the original library will remain untouched. The new sorted library will be created separately. If you would like to delete the original unsorted photo library, the `eraseOldLibrary` variable can be changed to `True`.

> IMPORTANT NOTE: You should backup your photo library before running any scripts. They have not been fully tested.

#### Running the script

Simply clone this repository, `cd` into it, and run `python3 libraryOrganiser.py`, specifying the path to the directory of the photos you wish to sort in the field which will appear when you run the script. The script will recursively run through any subdirectories in this folder.
