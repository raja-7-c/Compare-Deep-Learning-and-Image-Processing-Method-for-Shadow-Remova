## Compare-Deep-Learning-and-Image-Processing-Method-for-Shadow-Removal

#Abstract
The Deep Learning Model is multi-tasking which
jointly learns both shadow detection and shadow removal. The
framework is based on a novel Stacked Conditional Generative
Adversarial Network (ST-CGAN), composed of two stacked
CGANs, each with a generator and a discriminator. Essentially,
a shadow image is given as input into the first generator, which
provide a shadow detection mask. That shadow image, merged
with its predicted mask, goes through the second generator to
finally get back its shadow-free image. Moreover, the two corre-
sponding discriminators will model the higher-level relationships
and global scene characteristics for the detected shadow region
and reconstruction via removing shadows, respectively. The image
processing method rectifies illumination using diffusion model
and the traditional binarization using K-means clustering.For the
documents the traditional image processing methods are superior
but the time complexity is a issue where as for natural images
the Neural net gives better results.
