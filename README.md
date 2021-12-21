# SI
Visualiza where you are in the SI network.   
![alt text](figs/Unknown-20.png)

Creat a gephi file using this line: nx.write_gexf(G, "test.gexf"). 
Import "test.gexf" file into Gephi (this is a professional tool can be downloaded from https://gephi.org) and add class label to your nodes. After adding class label your data should look like this: 
![alt text](figs/data.png)

In gephi work place, change node color according to class (SI/non-SI):   
![alt text](figs/node_color.png),   
and change edge color accordding to weight:   
![alt text](figs/link_color.png)

Then adjust network shape using "Force Atlas", "Label adjust" and "non overlap":  
![alt text](figs/shape.png)![alt text](figs/label_adjust.png). 

Then expansion if needed. In preview, the network should look like this:  
![alt text](figs/network_preview.png)

