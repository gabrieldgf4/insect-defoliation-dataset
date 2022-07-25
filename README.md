# insect-defoliation-dataset

Defoliation estimation methods are difficult to be compared with each other because there is no benchmarking for this purpose. Researchers use their own database which is not accessible to the general public. 

Then, the data are restricted to those presented in the published works and it is not possible to verify the variability of the samples such as lighting conditions, leaf format and position, and background complexity. Also, leaf images with damage caused by real insects or artificial leaf canopy damage used in experimental tests are difficult to reproduce in order to compare the results.

In this sense, we organized this database with model data (or training) and test data. We indicate the images used in the construction of template images and the images used in the tests. For the test images, we indicate their defoliation percentage in three groups: from 1 to 15%, from 16 to 30%, and from 31 to 45%. The size of the images is 256 x 256.

This dataset contains 12 plant species: apple, blueberry, cherry, corn, grape, peach, pepper, potato, raspberry, soybean, strawberry and tomato. It is based on the PlantVillage dataset which can be accessed here [https://github.com/spMohanty/PlantVillage-Dataset](https://github.com/spMohanty/PlantVillage-Dataset) or here [https://github.com/gabrieldgf4/PlantVillage-Dataset](https://github.com/gabrieldgf4/PlantVillage-Dataset).

Original papers URL: 

[https://www.sciencedirect.com/science/article/pii/S2772375522000211](https://www.sciencedirect.com/science/article/pii/S2772375522000211)          
[https://ieeexplore.ieee.org/document/9529869](https://ieeexplore.ieee.org/document/9529869)

If you use this project, cite:

    @article{gabrielISWA2022,
        Author = Author={Vieira, Gabriel and 
                  Fonseca, Afonso and
                  Sousa, Naiane and
                  Ferreira, Julio and
                  Soares, Fabrizzio},
        Title = {An automatic method for estimating foliar defoliation with border damage},
        journal={Intelligent Systems with Applications},
        volume={},
        pages={},
        doi={},
        url = {},
        year={2022}
    }

![alt tag](https://user-images.githubusercontent.com/63321757/180873122-244e57c0-21e6-4990-9120-74d8df3f726a.png)

You can download the code by:

    git clone https://github.com/gabrieldgf4/insect-defoliation-dataset.git
    cd insect-defoliation-dataset
    
    
