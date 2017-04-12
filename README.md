# Regex-to-DFA-to-Visualization
This repository is based on conversion of a Regular expression to a NFA then DFA and finally visualizing it as an image.

The dot file so generated can be viewed in following ways :

1. Convert it to .png/jpg using any online converter
2. Download GraphViz software and use gvedit 
3. If you use linux, you can install graphviz using apt  and then do the following
    i.  dot -Tpng out.dot > out.png  (If the output file name is "out.dot")
    ii. display out. 
    
In this way you finally get the image of DFA.
You can define the delta function as per your transitions in the finite automata.

Note : Sometimes the dot file generated may contain some extra double quotes which you can manually remove using any editor!
