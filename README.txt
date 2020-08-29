FileCleaner is a simple Java program that semi-automates the process of converting technical documents to sentence-per-line (SPL) format,
removing bibliographic references, and replacing problematic formatting with appropriate designations.

Before attempting to run FileCleaner, make sure all the necessary files ARE IN THE SAME DIRECTORY AND HAVE BEEN EXTRACTED, IF NECESSARY.

After FileCleaner is run, a plain text file containing the technical document's content must be selected, and the program then automatically
converts it into SPL format. Then, sentence by sentence, it identifies which sentences may contain problematic text (including broken formatting,
math, and bibliographic references) and brings them to your attention. If you find something you want to get rid of, select "yes" when the program
asks if you'd like to make changes to the sentence.

It will then ask for the start and end characters of the problematic section. If it's a bibliographic reference you'd like to delete, make sure you
select leading and trailing spaces, as everything in the span of selection will be deleted. If the section you'd like to modify is too long for the
program to display, modify as much as you can, and the program will let you modify more of the section after the initial modification.

For equations, inequalities, and expressions, select the bounds of the section and then click on the appropriate designation. The section will be replaced
with "EQUATION" or "INEQUALITY" or "EXPRESSION" automatically.

The sentences already parsed will be written to a background frame so you can be mindful of the progress already made.

When file parsing is complete, you will have the option to save your changes to a file. Make sure you don't try to overwrite an existing file.

After the file is saved, the program aborts.

This folder contains several files: icsi.jpg, which is the logo displayed by the program; License.txt; Cleaner.java, which is the Java code; FileCleaner.jar,
which can be run out-of-the box without compilation; dummy_example.txt, which is a document containing snippets of formatting on which FileCleaner can be
run to gain familiarity with the software; and FileCleaner_Walkthrough.mp4, a video that shows FileCleaner being used to clean dummy_example.txt.

Future improvements on this tool are encouraged. For example, one possible improvement is to preserve equation labels, if they're included.