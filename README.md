# bv-working-data

This repository is reseverd for files that are being manually changed. Data in `data/editions` should be copied **manually** from the [source-folder](https://github.com/bundesverfassung-oesterreich/bv-transkribus-export/tree/main/editions) in the bv-transkribus-export-repository.
Whenever data are being pushed to this repository, they will be fetched automatically by the [data-repository](https://github.com/bundesverfassung-oesterreich/bv-data), where they will be further processed to be finally published at [bv-static](https://github.com/bundesverfassung-oesterreich/bv-static) as a static webpage.


To edit files in this repository follow these steps:
1. **install Oxygen XML Editor**
2. **install the project plugin**\
Oxygen: `Help` (in top bar) > `Install new add-ons` > paste the link for the project plugin into the url-field `Show add-ons from:`, select the plugin and hit install\
 (link: `https://bundesverfassung-oesterreich.github.io/bv-schema-framework/ADDON/b-vg-addon.xml`)

3. **install the git plugin**\
Open the menu `Help` (in top bar) > `Install new add-ons`.\
Type "git" in the text field Type filter text.\
You can see a plugin called Git client. Check the box on the left to select the plugin and click Next.\
Check the box to accept the licence terms and click Install.
Click OK to close the info pop-up and close Oxygen.
3. **restart Oxygen**
4. **create an empty folder in your file-system, you will store the project data there**
5. **with the Oxygen git plugin clone this repo**
In the `destination path` field, provide the path to the directory you just created
6. **close Oxygen**
7. **copy [this file](https://raw.githubusercontent.com/bundesverfassung-oesterreich/bv-schema-framework/main/b-vg.xpr "download") into the directory you just created / cloned to**
8. **Open Oxygen**
9. With the git plugin clone [the source repository](https://github.com/bundesverfassung-oesterreich/bv-transkribus-export). If you want to edit a new file, copy it *from the editions folder of the source repository to the your local data/editions folder in this (bv-working-data) repository*. Then open the file in Oxygen, edit and commit it.
