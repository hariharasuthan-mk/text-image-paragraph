# text-image-paragraph

Create a Drupal 8 module that provide a paragraph type (ref: paragraph contributed module) with the following fields.

Title - Text field
Description - Text field
Image - image field
Position - select list with the following values - Left, Right
Wrap text - checkbox with default unchecked.

The module should provide the required paragraph type and the template required to render it. 
The image should display on the left column or right column based on the section in the position field. 
And the text in the description should wrap the image based on the value in the checkbox.
If the checkbox is not checked the image and text should be in 2 columns. 
The position value should be considered in case of text wrapping as well.
You can use bootstrap classes and assume that the site uses bootstrap 4 css framework ie the bootstrap files are already included. 

Acceptance criteria: 
Install the module provided in a Drupal 8.7 instance.
The paragraph type should be available in the list of paragraphs available in the system.
In a content type, the site builder should be able to add a entity reference to the paragraph type created.
When a content author creating a node of the content type which enable this paragraph type, the specific paragraph type can be used to upload the image 
and set the position and text wrap option.
When node is viewed, the content should be displayed as specified.
