## Definitions
- Background: Static image layer;
- Object: Lives within the space of the level and scales to the background;

## Conventions

### Naming Files

The filename starts with the contents -- what the image is. This brief description is all lowercased and hyphenated.
- contents-of-file_widthxheight.extension;

If the contents pertain to a specific component of an object, the object is named first and then the component. For example,
- player-left-arm.png

If there are multiple files that contain the same object components, but different dimensions, then the description is followed by an underscore and the dimensions of each image, separating width from height by an 'x'.
- player-left-arm_250x250.png
- player-left-arm_500x500.png

#### Don'ts
- Avoid version information in the filename;
- Avoid spaces in the filename;
- Avoid verbose or long filenames

### File Formats
- JPG for backgrounds;
- PNG for everything else.

### Image Dimensions

The screen size is 2650 x 1600.  Make sure your graphics look good on this screen size (i.e. they are proportional to other graphics).
- Backgrounds: 2650 x 1600
- Proportionality: All objects are drawn to the scale with the maximum background size. This means when your objects are placed in the level, they look appropriately sized relative to other objects and the background.
- See playerReference.png for the approximate size of the player. Use this to develop your graphics.
