# figtreeshowlabelbydefault
A fix to show bootstrap value on figtree startup. 
Figtree https://github.com/rambaut/figtree is a powerful phylogenetic tree viewer, but it does not show labels(e.g. bootstrap value) by default. To show those labels, users have to click the 'Branch Labels panel' and choose. This is not so convenient when there are dozens of tree files to be viewed.
This version automatically show label from tree on startup. When no label found, it shows the branch times.
Install:
Put 'figtree.jar figtreepanel.jar figtree-pdf.jar figtree.war' to Path_to_figtree_lib (replace the original files): e.g. 'FigTree_v1.4.3/lib/', then run figtree as usual;
Or simply typle 'java -Xms64m -Xmx512m -jar figtree.jar';
Compiled and tested on debian8.
