Welcome to Creatura community localization project.

If You are fluent in a language other than English, have some time to spare, and wish to become credited in game as one of Creatura translators, please join our community effort of localizing Creatura into other languages. 

Creatura localization file is quite a huge task for one person to translate, but partial commits of any size, even if it's just finding a single misspelled word or localizing one dialogue sentence, help a lot of folks interested in this game, but not comfortable in reading the interface or scenario dialogues in original language. 

To start translating download and install Git, authorize on GitHub, open Git Bash in empty directory, and follow below steps in Git Bash window:
1. Clone Git repository:</br>
$ git clone https://github.com/koksny/creatura-localizations.git

2. Create branch for new language, or checkout existing one. Make sure branch name descripts selected language:</br>
$ git checkout -b German

If working on new localization:
- Create or import localization .xml file, with filename matching the template.
- Add localization file to repository:</br>
$ git add Locale_de.xml

3. Translate the file.
4. Commit the changes to the localization .xml files. Describe done changes in the message part:</br>
$ git commit -m "Leave here short message describing changes in this commit"

5. Push the changes to GitHub for review. Make sure branch name descripts selected language:</br>
$ git push -u origin German

Once approved, the localization will become part of the Creatura release, with other people also able to iterate and improve upon it over time.

Please commit localization file name format according to below template:

    "Locale_" + Lower Case ISO 3166 Alpha-2 Country Code + ".xml" 
    for example: "Locale_de.xml", "Locale_fr.xml", "Locale_jp.xml"

List of Alpha-2 ISO-3166 country codes can be found on:
https://en.wikipedia.org/wiki/List_of_ISO_3166_country_codes

All new branches updates will be reviewed and merged to master branch if accepted. Please leave a comment in the translated file, with name to add into credits.
