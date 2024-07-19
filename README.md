# SimpleSemanticTemplate
This repository is intended for the sole purpose of allowing beginners in Python programming (or in general) to start versioning their code systematically.

And can build their own individual template from it.


# How to implement your own custom commit message template (locally)

  Not that you have some steps todo before you can use it.

## Create .gitmassage
  
  1. Go into your repositorie
  2. Create in your repositorie folder a text file like .txt and name it .gitmessage.txt. (Or you can take the template I made. If you do this, then you can go directly to the "git configure" part).
  3. After you create the .gitmessage.txt you can copy the template file or use the template to create your personal template.
  4. **Very Important Step** DON'T FORGET TO SAFE your file from time to time. (Maybe this happened to me one or two time while I wrote everything).

  If you are good to go with your .gitmassage template, then we can start with the configure part.

## git configure

  1. Open your Terminal. (I personally use VS Code)
  2. Navigate to your repositorie folder.
  3. After you are in your repositorie folder (Which should look like this "..\github\myproject").
  4. Type in your terminal this command to set the path for your commit template: `git config --local commit.template .gitmessage.txt`.
     (*to mention*: This set you commit.template only for your selected repositorie. Also, if it wound work from the beginning, enter the datatype from your .gitmessage)
  5. Now, you can verify your selected commit template with this command: `git config --local --get-all commit.template`. You should get a print with the template name like ".gitmessage.txt"
     (*to mention*: Be sure you are sill in your repositorie folder, *Step 3*)

  Now you can use your custom commit template for your specific repositorie.
