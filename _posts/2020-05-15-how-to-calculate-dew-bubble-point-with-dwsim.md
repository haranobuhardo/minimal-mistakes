---
title: "How to Create Phase Diagram with ChemSep"
categories:
  - engineering
tags:
  - chemsep
  - learn
  - engineering
  - tutorial
  - phase-diagram
header:
  teaser: /assets/images/chemsep-book-cover.jpg
  image: /assets/images/chemsep-book-cover.jpg
  caption: "Photo credit: [**Amazon**](https://www.amazon.com/ChemSep-book-Ross-Taylor/dp/3831110689)"
---
  
**ChemSep** is a column simulator for distillation, absorption, and extraction operations. ChemSep project was founded in February 1988 by Arno Haket, Harry Kooijman and Ross Taylor. This software was designed to be easy to use by students with no experience of engineering software, while having sufficient flexibility and power to appeal to expert users. ChemSep released a LITE version in 2006, which is free-of-charge, so that anybody can test-drive the program.  
  
One of the most common problem we frequently face in thermodynamic is creating a phase-diagram for a mixture. ChemSep can help you to create this by:  
  
1. Open your ChemSep application **(wincs.exe)**, mine version is 8.14, so this tutorial might not work or different in newer or older version  
2. Name your Project’s title, I’m going to name it **Phase Diagram for Mixture of Acetone and Benzene**
<figure>
<a href="\assets\images\phase-diagram-chemsep-1.jpg"><img src="\assets\images\phase-diagram-chemsep-1.jpg"></a>
</figure>  
3. Click on the **Component** label, and then find the compound that you want to add into the mixture, in this case it’s Acetone and Benzene. After you found the compound, click on it, and then press **Add** button to add that compound to the **Selected Components List**
<figure>
	<a href="\assets\images\phase-diagram-chemsep-2.jpg"><img src="\assets\images\phase-diagram-chemsep-2.jpg"></a>
</figure>  
4. Select proper K-Value, Active Coefficient, Vapor Pressure and Enthalpy of the Thermodynamics Model that you want to use (in this case we’re going to use DECHEMA for K-Value, UNIFAC for Activity Model, Antoine for Vapor Pressure, and None for the Enthalpy)
<figure>
	<a href="\assets\images\phase-diagram-chemsep-3.jpg"><img src="\assets\images\phase-diagram-chemsep-3.jpg"></a>
</figure>  
5. Go to **Analysis – Phase diagrams – Binary** menu option
<figure>
	<a href="\assets\images\phase-diagram-chemsep-4.jpg"><img src="\assets\images\phase-diagram-chemsep-4.jpg"></a>
</figure>  
6. After **Binary Phase Diagram** opened, select the phase diagram type, Temperature (you can compare two temperature), and number of points of your diagram. Lastly, press the **Calculate** button to generate the Phase Diagram
<figure>
	<a href="\assets\images\phase-diagram-chemsep-5.jpg"><img src="\assets\images\phase-diagram-chemsep-5.jpg"></a>
</figure>  
7. That’s it! If you want to copy the diagram just simply right click on the diagram and choose **Copy plot as** and select in what type of clipboard you want to copy the diagram.  

This program really made creating a phase-diagram for a mixture really easy, but I think so far it only support Binary and Tersier Phase Diagram. Could i have any more information about how do we can use this software to create a phase-diagram for Multiple-Component mixture.  

If you want to know more about this amazing software, you may visit [www.chemsep.org](http://www.chemsep.org/) or simply download the guide book [here](http://www.chemsep.org/book/docs/book2.pdf).  
  
> Stay hungry, stay foolish.