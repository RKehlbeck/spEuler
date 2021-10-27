# spEuler: Semantics-preserving Euler Diagrams

## About

spEuler is a technique to visualize curves of Venn and Euler diagrams.  
The produced diagrams are mostly monotone and have little concurrency of curves!  
In this repository you will find a link to the current, preliminary tool, the citation, and in the future the code.  

## Citation


    @article{Kehlbeck2021SPEULERSemantics,
      title     = {spEuler: Semantics-preserving Euler Diagrams},
      author    = {R.Kehlbeck,  J. Görtler, Y. Wang, O. Deussen},
      journal   = {{IEEE} Transactions on Visualization and Computer Graphics}, 
      year      = {2021},
      pages     = {1--1},
      doi       = {10.1109/tvcg.2021.3114834}, 
    } 

# Online Tool

We are hosting preliminary version of the tool at [http://rkehlbeck.github.io/spEulerTool](http://rkehlbeck.github.io/spEulerTool).  


# FAQ

**Q: What kind of data can be visualized with spEuler?**

**A:** The data has to be set-typed. Each set intersection needs to have both at least one superset and one subset, with the exception of the empty set and the full-set.

**Q: Can spEuler create area-proportionate Euler/Venn diagrams?**

**A:** Currently, the tool cannot create area-proportionate diagrams.  However, we plan to extend our work to create these in future iterations of the tool.

**Q: Can spEuler automatically visualize datapoints in the diagrams?**

**A:** Currently, the tool cannot show datapoints, such as text or images in the diagrams.  However, we plan to extend our work to automatically visualize them in the future.

**Q: Can I visualize my own datasets?**

**A:** Currently, it is only possible to reproduce the figures from the paper, and generate Venn diagrams for up to 16 sets.   
However, Venn diagrams with more than 9 sets might take a long time to compute.

# Code

The code will be released in this repository in the future.

# Timeline 

- [ ] Release code
- [ ] Allow for visualization of custom datasets
- [ ] Automatic integration of datapoints
- [ ] Lots more to come :)

# Thanks
Thanks to [Matthias Albrecht @biosmanager](https://github.com/biosmanager) for his invaluable help during the implementation of the tool.