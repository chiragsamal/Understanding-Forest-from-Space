# Understanding-Forest-from-Space

Every minute, the world loses an area of forest the size of 48 football fields. And deforestation in the Amazon Basin accounts for the largest share, contributing to reduced biodiversity, habitat loss, climate change, and other devastating effects. But better data about the location of deforestation and human encroachment on forests can help governments and local stakeholders respond more quickly and effectively.

In the winter, I was learning [Practical Deep Learning for Coders by fast.ai](https://course.fast.ai/), so I decided with solving a problem of my choosing by applying machine learning algorithms and techniques learned throughout the course. I decided to choose an area which I am adamantly passionate about: saving the environment. I learned of a past Kaggle competition which involved classifying satellite images of the Amazon rainforest through the fantastic fast.ai course.

You can find the competition here, named: [Planet: Understanding the Amazon from Space](https://www.kaggle.com/c/planet-understanding-the-amazon-from-space)
I decided to embark on my journey of detecting deforestation of the rainforest, and see just how far up the Kaggle leaderboard I could climb.

The Amazon is the largest and most biodiverse tropical rainforest in the world, covering an area of 2.1 million square miles. It is comprised of an estimated 390 billion individual trees divided into 16,000 species. The Amazon has been referred to as the “lungs of the planet”, as it helps to stabilize the earth’s climate and slow global warming by fixing CO2 and producing 20% of the world’s oxygen.
Since 1978 over 289,000 square miles of Amazon rainforest have been destroyed across Brazil, Peru, Columbia, Bolivia, Venezuela, Suriname, Guyana, and French Guiana. Every minute, the world loses an area of forest the size of 48 football fields. There is concern that the destruction of the forest will result in loss of biodiversity, habitat loss, and the release of the carbon contained within the vegetation, which could accelerate global warming. Better data about the location of deforestation and human encroachment on forests can help governments and local stakeholders respond more quickly and effectively.

<img src="https://github.com/chiragsamal/Understanding-Forest-from-Space/blob/master/Images/amazon_forest.jpg" alt="Paris" class="center">

Planet, designer and builder of the world’s largest constellation of Earth-imaging satellites, will soon be collecting daily imagery of the entire land surface of the earth at 3-5 meter resolution. While considerable research has been devoted to tracking changes in forests, it typically depends on coarse-resolution imagery from Landsat (30 meter pixels) or MODIS (250 meter pixels). This limits its effectiveness in areas where small-scale deforestation or forest degradation dominate.


Furthermore, these existing methods generally cannot differentiate between human causes of forest loss and natural causes. Higher resolution imagery has already been shown to be exceptionally good at this, but robust methods have not yet been developed for Planet imagery.

The competition contained over 40,000 training images, each of which could contain multiple labels, generally divided into the following groups:
 - Atmospheric conditions: clear, partly cloudy, cloudy, and haze
 - Common land cover and land use types: rainforest, agriculture, rivers, towns/cities, roads, cultivation, and bare ground
 - Rare land cover and land use types: slash and burn, selective logging, blooming, conventional mining, artisanal mining, and blow down

### Problem Statement
The goal of this project is to track changes in the Amazon rainforest due to deforestation using satellite image data. The data has been provided by Planet and hosted on Kaggle as part of a previous competition — Planet: Understanding the Amazon from Space. The labels for this task were chosen in collaboration with Planet’s Impact team and represent a reasonable subset of phenomena of interest in the Amazon basin. The task is a multi-label image classification problem, where each image will have one and potentially more than one atmospheric label and zero or more common and rare labels.


<img src='https://github.com/chiragsamal/Understanding-Forest-from-Space/blob/master/Images/Amazon%20Forest.png'>


#### References
- [Practical Deep Learning for Coders](https://course.fast.ai/)
- [Kaggle Notebooks](https://www.kaggle.com/c/planet-understanding-the-amazon-from-space/notebooks)
- [Detecting Deforestation from Satellite Imagery](https://towardsdatascience.com/understanding-the-amazon-rainforest-with-deep-learning-732bfb2eca6e)
- [Planet Amazon Deforestation](https://github.com/planetlabs/planet-amazon-deforestation)
