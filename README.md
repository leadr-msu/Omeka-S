# Omeka-S
Omeka S Tutorial

===Dashboard Navigation===
On the dashboard, there is a navigation bar on the left and the main work area on the right.  "Manage Resources" provides links and summary accounts for Items, Item Sets, Vocabularies, and Resource Templates. "Manage Sites" lists all sites within the Omeka S installation.  Clicking on the name of a site will direct users to the public view, while clicking on the edit button (pencil icon) will direct users to the editing base.  

On the left-side navigation column, users will see a section heading for "Resources."  This contains all of the tools to build content in Omeka S: 
*Items 
*Item Sets
*Vocabularies
*Resource Templates

Below these options the user will see the the Administrator system settings to manage all websites on the Omeka S installation, including: 
*Users (single or batch-add)
*Modules (plug-ins to extend functionality)
*Jobs
*Settings

===Key Terminology and Concepts===
*'''Item''' - A digital representation of a piece of content in which you can attach metadata and upload multiple forms of media.  Items are the building blocks of every Omeka platform, but function a little differently in Omeka S. When users click on the pencil "edit" icon, it will take them to an interface where they will enter metadata information. A new feature is that users will choose which metadata fields they would like to complete based on a list of four different "Properties" that will appear in a side bar on the right side of the screen. Here, users can choose fields from the property lists: 
**Dublin Core (Omeka's standard metadata fields)
**Bibliographic Ontology
**Friend of a Friend (Ideal for genealogical projects)
   Example: Usually a primary or secondary source such as a painting, document, legislation, interview clip, book, newspaper, etc.
*'''Item Set''' - A group of "Items"  organized around a similar inherent features, like an idea, person, or place.  If multiple Items have the same owner/contributor or archival/museum collection, then creating an Item Set for these objects is an appropriate form of organization. Every Item Set will have its own metadata, and is structured very similarly to "Collections" in Omeka Classic.  The difference is that any Item can appear in one or more Item Sets as users deem necessary.
   Example: The Item Set titled: "William Shakespeare" would include include the Items: ''Romeo and Juliet'', ''Othello'', and ''Macbeth''.

A new feature of Omeka S is the ability to enter an existing Item or Item Set as the value for a property field.  For example, the Item Set based on "William Shakespeare" can be entered into the "Author" field of an Item. This way, any work with the same author will be connected together.

*'''Resource Templates''' - Allows users to create custom sets of metadata properties from any of the categories or a combination of them, and name it.  You can then select the resource template when creating an Item or Item Set and it will be added to the metadata form. This feature can simplify the workload when adding a multitude of similar items. This function is similar to "Item Type" in Omeka Classic, but has more flexibility in type-specific metadata.

==Adding and Managing Content==
===Create a Website===

===Items===
To add an item, follow these steps: 

'''1.''' Go to "Items" under resources and then click the gray button "Add new item." 

'''2.''' Select a resource template that best applies to the item's type (film, artwork, textual work, a custom template, etc.).  Also select a "class" to claim a metadata type.  

'''3.''' Adding a resource template and class will change the kinds of metadata fields available to enter information. To add more fields, skim through the "properties" column on the right side of the page and choose which fields you would like to add to your item's metadata information.  Choose properties from "Dublin Core," "Bibliographic Ontology," and "Friend of a Friend" as the user sees appropriate for their item. 

'''4.'''  Click the media tab to upload media from your computer, through a URL, HTML, IIIF image, oEmbed, or Youtube.  

'''5.''' Select the "Item set" tab to add the item to a pre-created Item set. (i.e.  This is where authors might connect their works to a specific donor, artist, creator, etc.).

'''6.''' Lastly, click "Add" and the item will appear in the list with the others.  Edit the item at anytime by selecting the pencil icon.

===Item Sets===

===Pages to a Website===

==The Sandbox ==
Learn how to use Omeka S by experimenting with their [http://dev.omeka.org/omeka-s-sandbox/login Sandbox]. It comes pre-populated with items, item sets, resource templates and websites. Users can practice uploading their own content as well.
   Log in with one of the following accounts
           omekasdemo1@example.com
           omekasdemo2@example.com
           omekasdemo3@example.com
   Passwords for each account are the username in the email address (omekasdemo1, etc).

== Modules ==
