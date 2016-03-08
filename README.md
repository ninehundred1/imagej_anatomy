# Quantify differences in the innervation of neuronal processes.

Simple ImageJ macro that lets you threshold an anatomy image to extract labeled structures. You can then divide the structures in two groups and quantify the differences in total labeling between those two groups.

If you believe there is a bias to one side in terms of labeling strength, this would allow you to quantify that by counting all labeled pixels without the backround and plotting a labeling profile.



## 1. Data Input


![Fig1](http://i.imgur.com/40lz9CA.jpg)

Here an example of GFP labeled neurons to run the script on.




## 2. Script Output

##### A. Areas differences
In the first step of the script the user can define two areas to compare. The labeling site was chosen to be compared by dividing it into left and right (see region 1 and 2). The calculated pixel count and ratio is written in the top left corner of the image.
![Fig1](http://i.imgur.com/IfNszva.jpg)



##### B. Binned distribution across labeling
In the second step the user can define areas across the site to bin and compare a bias in lateral innervation density. These are two user defined areas to be binned.

![Fig2](http://i.imgur.com/YdiItrc.jpg)


##### C. Binned distribution across labeling - OUTPUT
This is the pixel distribution across both of above defined bin areas.

![Fig2](http://i.imgur.com/I0Yjsqs.jpg)


##### D. Binned density map 
Next a binned innervation map is calculated allowing to visualize any bias in innervation.

![Fig2](http://i.imgur.com/dGpXwdK.jpg)



##### E. Summary image 
This image serves as a summary of all steps taken above.

![Fig2](http://i.imgur.com/mkqdZKM.jpg)
