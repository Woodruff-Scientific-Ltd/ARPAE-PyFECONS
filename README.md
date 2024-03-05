This Github contains a branch for each base case, and one for the benchmark cases. Each branch contains the code in a .ipynb file, and a file named 'Text.txt' with the corresponding Google Drive with the .tex file templates that get hydrated when the code is run, and an overelaf document which acts as the interface between the code and the text, and where the final report is compiled.

1. Download the code notebook .ipynb file or save a copy into google colab (search google colab, then file/upload notebook/ Github/ search for this repo using the url and select a code from the MFE, IFE etc.).
2. Open the Overleaf link. Link: https://www.overleaf.com/3634545777xwcczwmwvvqb#045b03.
3. Here there are folders for each costing case. Select one, inside there are 'Originals', 'Modified', 'Costing_ARPA-E_x_Modified', 'Costing_ARPA-E_x_Originals' and others. To compile a report with template folders, run 'Costing_ARPA-E_<x>_Originals'. To edit text, edit files in 'Originals'. Edits made to files in the 'Modified' folder will be overwritten when the code is run.
4. Become a Github collaborator and generate a PAT (ensure it has 'repo' access).
5. Input PAT into first cell of code.
6. Enter inputs in the code, and run all cells. This will overwrite 'originals' templates.
7. Go to overleaf and 'pull' from github into overleaf.
8. Compile the 'Costing_ARPA-E_<x>_Modified' .tex file for the corresponding case.
9. A report should have compiled with the placeholder variables replaced.

10. To edit the text, edit the 'originals' .tex files corresponding to the cost category you would like to edit, in the case folder you are working on.
11. Go to 'Github' on the left tab, and 'push'.
12. Restart code (in colab go 'Runtime/Disconnect and delete runtime' then 'run all'), and repeat steps 3-6.
