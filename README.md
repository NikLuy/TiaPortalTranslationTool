# TiaPortalTranslationTool
This is a Tool to have all the Machine translation stored in a MySql Database. With the files exported from Tia, the Tool replace numbers and units with a placeholder so the numbers of translations gets significant down.

# Problem with Tia
The Problem wit tia or Another HMI solution is, that the Text are wholes strings. To translate every entry has to translate on ist own line even if they are the the sae or almost the same texts. For some machines wi had to translate about 10000 rows of text. For the translation we have to pay per row, so ther where two Options 
pay much or merge the text for translation by hand. 

# Solution
Do the merging by hand was a pain and took alot of time. So i came with this tool it merges the translations together. In my example about 10'000 rows we cam to around 2500-3000 rows in the first time. for the next machines there where only about 1-400 rows to translate because of the database. 

# Application 
I made the application some years ago in a Winform. To publish i decided to write it new as a WPF MVVM .Net 6 Application. If hou hava any Improvements just let me know

