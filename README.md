# Salesforce Diagram Technology Package (Sparx EA)
This is a Sparx Enterprise Architecture custom technology package that provides a diagram and components that align with the Salesforce Architecture diagram style.

No Salesforce assets are actually included in this package, you can download icons and other resources from the various Salesforce links below.  

I will be including a BIMP file (GIMP batch automation) that allows you to take the icons you download from Salesforce and generate ones that look like the ones in https://www.lightningdesignsystem.com/icons/ The downloaded icons are white with a transparent background by default.

## Elements
 ![Toolbox Items](/md-images/toolbox.png)

The collapsed cards are fairly simple items and are used for the collapsed and the container elements.

All items support both the handdrawn style and the custom style in Sparx, though the custom style removes the shapescript style.

The default font on Windows is Calibri and should be set to 10pt to replicate the style completely.  Salesforce San font is available though I'm not sure of the licencing. On Windows, again, Microsoft Sans Serif is a close match.

### Collapsed Cards (Icons)
<img src="/md-images/CollapsedCardSF.png"  align="left"/>

These are standard collapsed cards with space in the top left corner for a icon.  Text value is held in the notes field of the object, it is also possible to change the colour.

The non Salesforce collapsed cards are the same apart from their default colour settings.  These can also be changed in the same way as the salesforce cards.

The cards also support multiline text, though this is largely manual.  Under the SF properties the text lines supports single or double lines.

These cards have space for an icon, though these are just images that are added to the model separately. 
<br><br><br><br>

### Collapsed Cards (No Icons)
This is similar to the cards with icons, but with out the space for an icon.  These are also useful for items within a container.
<br><br>
### Detailed Card
This provides some extra features over the collapsed versions.  This has the space for an icon in the top left, and icons along the bottom.
![Toolbox Items](/md-images/SFDetailedCard.jpg)
<br><br>
Selected one of the following
+ RecordType
+ Owner
+ Custom Object
+ Free Text

These cards also support both multiple text lines.

### Connectors
There are two types of connectors, an integraiton style which can show direction, and an ERD style one showing multiplicity. Both line types can have their style (solid,dotted,dashed...) configured by the tag value.  Both connectors also support the quick linker option in Enterprise Architect.

#### Integration
This shows a simple link between two objects.  You can specificy the direction and based on what you've selected appropriate solid arrows are show.  This connector also supports the UML style of multiplicity (e.g. 0..\*) and displays this as expected.
![Toolbox Items](/md-images/IntegrationAssocation.png)

#### ERD Style
This is more for the data objects of the underlying design (level 4 diagrams).  This uses the ERD or crows foot notation for each end.
![Toolbox Items](/md-images/ERDAssocation.png)


## Icons 
By default the icons from Salesforce are white with a transparent background.  The BIMP file will convert the images to PNG with a coloured background and with rounded corners.  The same as they appear on the Salesforce page.
![Toolbox Items](/md-images/icons.png)
The BIMP [BIMP Details](/bimp-readme.md) page contains details about how to use the BIMP file, or how to create your own.

<br><br>

Some icons though are used with a white circlar background.  I've not found a way to create this yet using BIMP.
To create this style, the MDG file contains three images, a white circle and two versions with borders.  These can be used to create the diagram style above.



## Salesforce Links
* https://medium.com/salesforce-architects/introducing-salesforce-diagrams-a8fa7bc4a3e
* https://www.lightningdesignsystem.com/icons/
* https://architect.salesforce.com/design/diagram-templates/how-to-diagram/
* https://architect.salesforce.com/design/diagram-templates/doc-implementation-templates/
* https://architect.salesforce.com/design/diagram-templates/kit-of-parts/


 
