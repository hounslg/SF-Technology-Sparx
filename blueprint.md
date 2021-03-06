## Blueprint Diagrams
These template covers the four levels as covered in the documentation and implementation templates page.  The last level can overlap with the data model notation, the example is of a data model.

All elements have one or more of the following custom properties.

![Custom Properties](/md-images/BlueprintObjectProperties.png)

The box width controls how the dividing line is drawn. If you resize the boxes width this affects this line due to the way in which shapescript works.  This allows you to move the endpoint of the line if needed.

The text lines controls the spacing from the top of the box, so if your text needs to wrap you can allow for this.  Again ideally this would be automatic, but this is a limitation of shapescript.

The other items vary based on the element you are working with and are fairly self explanatory.


### Elements
 ![Toolbox Items](/md-images/toolbox.png)

The collapsed cards are fairly simple items and are used for the collapsed and the container elements.

All items support both the handdrawn style and the custom style in Sparx, though the custom style removes the shapescript from the elements.

The default font on Windows is Calibri and should be set to 10pt to replicate the style.  Salesforce San font is available on the net though I'm not sure of the licencing. On Windows, again, Microsoft Sans Serif is a close match.

### Collapsed Cards (Icons)
<img src="/md-images/CollapsedCardSF.png" >

These are standard collapsed cards with space in the top left corner for a icon.  Text value is held in the notes field of the object, it is also possible to change the colour.

The non Salesforce collapsed cards are the same apart from their default colour settings.  These can also be changed in the same way as the salesforce cards.

The cards also support multiline text, though this is largely manual.  Under the SF properties the text lines supports single or double lines.

These cards have space for an icon, though these are just images that are added to the model separately. 

### Collapsed Cards (No Icons)
This is similar to the cards with icons, but with out the space for an icon.  These are useful as a container to hold child items.
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