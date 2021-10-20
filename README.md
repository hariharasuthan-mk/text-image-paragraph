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



Usages
------

1.Install text+image module, it will provide Example content type and related configuration and Paragraph "Text + Image" (Title, Description, Image, Position, Wrap text) . Paragraph field Reference
2.Copy the template "paragraph--text-image--example.html.twig" to current theme ( bootstrap4 based/sub theme )
3.Add the node content as domainname/node/add/example as per attached screenshot-1
4. Refer the following screenshot 2-4
