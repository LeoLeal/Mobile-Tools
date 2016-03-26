# Illustrator Mobile Assets Export

These are a set of tools for Adobe Illustrator used to export vector assets to the many formats used on Mobile Development (currently Android and iOS only)

## Action_Bar_Icons_Export.jsx

Exports ActionBar Icons converting them to both Android Themes (Light and Dark) and iOS (using default color)

### How to Use

* Create an Illustrator file of 48x48 Pixels (Default and MDPI Resolution size).
* Design your Icons using the Design Guidelines for Android and iOS. Use the color you want to use for iOS icons.
* Each icon must be a compound path in a separate layer. The Name of the Layer will be the resulting file's name.
* Go to Illustrator Export Menu using Other Script...
* Choose the file named after this section's title and select It.
* The Files will be placed in a folder called "out" in the script's folder.
* Android files will be placed separatelly for each Android theme.


## Pure_Assets_Export.jsx

Exports Assets converting them to Both Android and iOS conserving their original size and colors.

### How to Use

* Create an Illustrator file of any size in pixels (using desired Default and MDPI resolution size).
* Design your assets using the Design Guidelines for Android and iOS. Use the color you want to use.
* Each asset must be a compound path in a separate layer. The Name of the Layer will be the resulting file's name.
* Go to Illustrator Export Menu using Other Script...
* Choose the file named after this section's title and select It.
* The Files will be placed in a folder called "out" in the script's folder.
