This script creates customizable guides around selected objects in Adobe Illustrator. Here's a detailed breakdown of its functionality:

Initial Checks:
Verifies that a document is open
Checks if any object is selected in the document
User Interface: Creates a dialog window with two main customization options:
Margin input: Allows users to specify the distance (in points) between the guides and the selected object
Color selection: Lets users choose the color of the guides from six options:
Cyan
Magenta
Yellow
Red
Green
Blue
Guide Creation: When the user clicks "OK", the script:
Creates four guides around the selected object:
Two vertical guides (left and right)
Two horizontal guides (top and bottom)
Places these guides at the specified margin distance from the object's bounds
Applies the selected color to all guides
Technical Details:
Uses the object's geometric bounds to calculate guide positions
Creates guides by making path items and converting them to guides
Uses CMYK color values for the guide colors
Handles errors gracefully with try-catch blocks


Example Use Case:

User selects an object in Illustrator
Runs the script
Sets margin to 10 points and selects "Red" as the guide color
Clicks OK
Four red guides appear around the object, each 10 points away from the object's edges
This script is particularly useful for:

Layout design
Creating consistent spacing around objects
Setting up print documents
Creating alignment references
Maintaining visual consistency in designs
