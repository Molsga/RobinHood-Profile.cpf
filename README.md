Names and Colours are straight out of the profile.cpf File.

"Enemy_Hero" are Guy of Guisbourne, Longchamp, Scathlock and Sheriff of Nothingham in that Order.

"Unit_Block_Head" is a base 64 Encoding of the Name and Colour etc. because it caused some issues in the Code with Carriage Return and New Line Feed interpretations of the Bytes

You can Only Change Values inside Unit Blocks, not the name or the colour of them.
Also don't try to change the Unit_Block_Head base 64 encoding probably.

How to Use:

1. Drop all the files into your Robin Hood/DATA/Configuration folder
2. Make a Backup of your Original profile.cpf File
3. If you already changed something about the profile.cpf File and wish to keep those Changes run the XML_Creator.bat, it turns your profile.cpf File into an equivalent .xml File
4. Run the CPF_Creator.bat, it opens the .xml File in your favorite Editor and waits for you to make changes in the File
5. After closing of the .xml File a new profile.cpf File is created with your changes
6. Run the Game
