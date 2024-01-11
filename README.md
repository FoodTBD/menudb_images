# menudb_images

This repository is for storing image assets for https://github.com/FoodTBD/menudb.


# Adding Menu Images

⚠️ Important: Git is not designed for large files nor binary files. Furthermore, even if one "removes" files, they remain in version history, so a repository grows irreversibly in size.

Before committing any image file, please downsize it as follows:

1. On macOS, control-click (or right click) on the input image file(s) and choose Quick Actions > Convert Image.
1. For "Format", choose JPEG. For "Image Size", use your best judgment, but as a guideline, stay under 500K.

To prevent accidentally committing very large files, there are `gitignore` rules to enforce this procedure.

To manually mark an image as downsized (as an exception to the above), name it "`*_sm.jpeg`.

Pushing to this repository will publish them via GitHub Pages. The resulting URL is of the form `https://foodtbd.github.io/menudb_images/menus/xxx/filename%20Large.jpeg`.

⚠️ The Convert Image quick action generates filenames with spaces. Don't forget to escape the spaces with `%20` when you use them.