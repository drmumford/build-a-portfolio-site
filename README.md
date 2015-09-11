This project uses Grunt to automatically create responsive images.

To leverage this functionality, you'll need to run 'npm install' after
cloning the repository. This will create the necessary dependencies,
as defined in the package.json file. The dependencies will be created
in a 'node_modules' directory.

Images that you want to be responsive must be put in the images_src
directory. Each image in that directory will have multiple images
output to the images directory, as defined in the Gruntfile.js file.

To create the responsive images, type 'grunt' on the command line.
