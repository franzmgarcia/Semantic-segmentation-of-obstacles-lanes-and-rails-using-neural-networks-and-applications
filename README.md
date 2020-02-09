# Semantic segmentation of obstacles, lanes and rails using neural networks and applications

Autonomous vehicles require strong detection systems to be safe for humans. This systems must to detect all the elements existing in the road systems, to have the ability of response in any situation. A good solution for this purpose, is the use of semantic segmentation of the elements in the road, using neural networks. In this work, I used the ERFNet network to do the semantic segmentation in real time, with an adaptation of the database BBD100K, modifying the labels to create new elements to be recognize. The training of the neural network provides an accuracy of 64.75%. Using the segmentation, I realized an algortihm to count the number of the roads existing in the road system, and the position of the vehicle in this system. This work, was realize in the Laboratory of Intelligent Systems, in Leganés, Spain.

## Results 

|Labels|IOU%|
| Pedestrians | 76.60 |
| Road Curb | 44.31% |
| Full single white | 32.53 |
| Full double yellow  | 63.38 |
| Full single yellow | 60.61 |
| Small vehicles | 37.70 |
| Medium vehicles | 74.38 |
| Big vehicles | 93.49 |
| Current lane | 88.24 |
| Parallel lanes | 76.27 |



![segmentation_Test1](https://github.com/franzmgarcia/Semantic-segmentation-of-obstacles-lanes-and-rails-using-neural-networks-and-applications/blob/master/Images/Test_merge_1.jpeg)

![segmentation_Test1](https://github.com/franzmgarcia/Semantic-segmentation-of-obstacles-lanes-and-rails-using-neural-networks-and-applications/blob/master/Images/Test_merge_2.jpeg)

![segmentation_Test1](https://github.com/franzmgarcia/Semantic-segmentation-of-obstacles-lanes-and-rails-using-neural-networks-and-applications/blob/master/Images/Test_merge_3.jpeg)

![segmentation_Test1](https://github.com/franzmgarcia/Semantic-segmentation-of-obstacles-lanes-and-rails-using-neural-networks-and-applications/blob/master/Images/Test_merge_4.jpeg)


![segmentation_Test1](https://github.com/franzmgarcia/Semantic-segmentation-of-obstacles-lanes-and-rails-using-neural-networks-and-applications/blob/master/Images/Kitty_merge_1.jpg)

![segmentation_Test1](https://github.com/franzmgarcia/Semantic-segmentation-of-obstacles-lanes-and-rails-using-neural-networks-and-applications/blob/master/Images/Kitty_merge_2.jpg)

![segmentation_Test1](https://github.com/franzmgarcia/Semantic-segmentation-of-obstacles-lanes-and-rails-using-neural-networks-and-applications/blob/master/Images/Kitty_merge_3.jpg)

![segmentation_Test1](https://github.com/franzmgarcia/Semantic-segmentation-of-obstacles-lanes-and-rails-using-neural-networks-and-applications/blob/master/Images/Kitty_merge_4.jpg)



![segmentation_Test1](https://github.com/franzmgarcia/Semantic-segmentation-of-obstacles-lanes-and-rails-using-neural-networks-and-applications/blob/master/Images/Kitty2_merge_1.jpg)

![segmentation_Test1](https://github.com/franzmgarcia/Semantic-segmentation-of-obstacles-lanes-and-rails-using-neural-networks-and-applications/blob/master/Images/Kitty2_merge_2.jpg)

![segmentation_Test1](https://github.com/franzmgarcia/Semantic-segmentation-of-obstacles-lanes-and-rails-using-neural-networks-and-applications/blob/master/Images/Kitty2_merge_3.jpg)

![segmentation_Test1](https://github.com/franzmgarcia/Semantic-segmentation-of-obstacles-lanes-and-rails-using-neural-networks-and-applications/blob/master/Images/Kitty2_merge_4.jpg)


