# Salesforce Diagram Technology Package (Sparx EA)
This is a Sparx Enterprise Architecture custom technology package that provides a diagram and components that align with the Salesforce Architecture diagram style.

No Salesforce assets are actually included in this package, you can download icons and other resources from the various Salesforce links below.  

I will be including a BIMP file (GIMP batch automation) that allows you to take the icons you download from Salesforce and generate ones that look like the ones in https://www.lightningdesignsystem.com/icons/ The downloaded icons are white with a transparent background by default.

## Elements
 ![Toolbox Items](/md-images/toolbox.png)

The collapsed cards are fairly simple items and are used for the collapsed and the container elements.

All items support both the handdrawn style and the custom style in Sparx, though the custom style removes most of the custom style.

### Collapsed Cards (Icons)
<img src="/md-images/CollapsedCardSF.png" width="300" align="left"/>

These are standard collapsed cards with space in the top left corner for a icon.  Text value is held in the notes field of the object, it is also possible to change the colour.

The non Salesforce collapsed cards are the same apart from their default colour settings.  These can also be changed in the same way as the salesforce cards.

These cards have space for an icon, though these are just images that are added to the model separately. 

### Collapsed Cards (No Icons)
This is similar to the cards with icons, but with out the space for an icon.  These are also useful for items within a container.

### Detailed Card
Card with extras

### Connectors
There are two types of connectors, an integraiton style which can show direction, and an ERD style one showing multiplicity. Both line types can have their style (solid,dotted,dashed...) configured by the tag value.

#### Integration
This shows a simple link between two objects.  You can specificy the direction and based on what you've selected appropriate solid arrows are show.  This connector also supports the UML style of multiplicity (e.g. 0..\*) and displays this as expected.

#### ERD Style
This is more for the data objects of the underlying design (level 4 diagrams).  This uses the ERD or crows foot notation for each end.


## Salesforce Links
* https://architect.salesforce.com/design/diagram-templates/how-to-diagram/
* https://architect.salesforce.com/design/diagram-templates/doc-implementation-templates/
* https://architect.salesforce.com/design/diagram-templates/kit-of-parts/


 
