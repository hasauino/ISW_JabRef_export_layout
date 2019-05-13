# ISW_JabRef_export_layout
Custom JabRef export layout suitable for ISW course. Used to export a HTML table of your entries collection. The HTML table has
the following colums:

- Citations
- Year
- Journal/Proceedings
- Title
- Author
- Reftype
- DOI/URL

# How to use

#### Add entry table column for citations:

1- go Options >> Preferences.
2- Select "Entry table columns".
3- Add "citations" columns there. Do not forget to set approperiate width for it. 

![alt text](https://raw.githubusercontent.com/hasauino/ISW_JabRef_export_layout/master/images/1.png "Add entry table column for citations")

4- For each entry you have, you need to add the citations field in its BibteX source.

![alt text](https://raw.githubusercontent.com/hasauino/ISW_JabRef_export_layout/master/images/2.png "Add entry table column for citations")

5- It should appear in the table like that:

![alt text](https://raw.githubusercontent.com/hasauino/ISW_JabRef_export_layout/master/images/3.png "Add entry table column for citations")

#### Add the custom export layout:

1- First clone/download this repository (this is the link https://github.com/hasauino/ISW_JabRef_export_layout.git)

2- In JabRef, go to ```Options```, then to ```Manage custom exports```.

3- Click on ```Add New```.

![alt text](https://raw.githubusercontent.com/hasauino/ISW_JabRef_export_layout/master/images/4.png "Add entry table column for citations")

4- Set fields as follows:

- Export Name: any name you want. When you actually export, this is the name that will appear in the export formats.

- Main layout file: choose ```tablerefsabsbib.layout``` which is in the repository you downloaded.

- file extension: .html

![alt text](https://raw.githubusercontent.com/hasauino/ISW_JabRef_export_layout/master/images/5.png "Add entry table column for citations")



#### Done:
When you export, there will be a new export option which you have named in the prevoius step. In the image below, it's names "isw":

![alt text](https://raw.githubusercontent.com/hasauino/ISW_JabRef_export_layout/master/images/6.png "Add entry table column for citations")

#### Done:
[example](https://hasauino.github.io/ISW_stuff/top100.html)
