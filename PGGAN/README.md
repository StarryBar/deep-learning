## NYU CS-9223 Deep Learning Project.
Collaborator: Runchen Hu, Shen Wang, Lifan Wang  



This repo is forked from https://github.com/tkarras/progressive_growing_of_gans  

We have done some minor changes in order to redo the experiment and achieve descent performace as described by the author.   
And we did our experiments either on Runchen's desktop with GTX 1080 and on NYU HPC Prince Tesla-P100. The CIFAR experiment took about 14 hours of training, and the CelebA experiment took another 14 hours.  


## Resources

* [Paper (NVIDIA research)](http://research.nvidia.com/publication/2017-10_Progressive-Growing-of)
* [Paper (arXiv)](http://arxiv.org/abs/1710.10196)
* [Result video (YouTube)](https://youtu.be/G06dEcZ-QTg)
* [Additional material (Google Drive)](https://drive.google.com/open?id=0B4qLcYyJmiz0NHFULTdYc05lX0U)
  * [Representative images (`images/representative-images`)](https://drive.google.com/open?id=0B4qLcYyJmiz0UE9zVHduWFVORlk)
  * [High-quality video clips (`videos/high-quality-video-clips`)](https://drive.google.com/open?id=1gQu3O8ZhC-nko8wLFgcNqcwMnRYL_z85)
  * [Huge collection of non-curated  images for each dataset (`images/100k-generated-images`)](https://drive.google.com/open?id=1j6uZ_a6zci0HyKZdpDq9kSa8VihtEPCp)
  * [Extensive video of random interpolations for each dataset (`videos/one-hour-of-random-interpolations`)](https://drive.google.com/open?id=1gAb3oqpaQFHZTwPUXHPIfBIP8eIeWNrI)
  * [Pre-trained networks (`networks/tensorflow-version`)](https://drive.google.com/open?id=15hvzxt_XxuokSmj0uO4xxMTMWVc0cIMU)
  * [Minimal example script for importing the pre-trained networks (`networks/tensorflow-version/example_import_script`)](https://drive.google.com/open?id=1A79qKDTFp6pExe4gTSgBsEOkxwa2oes_)
  * [Data files needed to reconstruct the CelebA-HQ dataset (`datasets/celeba-hq-deltas`)](https://drive.google.com/open?id=0B4qLcYyJmiz0TXY1NG02bzZVRGs)
  * [Example training logs and progress snapshots (`networks/tensorflow-version/example_training_runs`)](https://drive.google.com/open?id=1A9SKoQ7Xu2fqK22GHdMw8LZTh6qLvR7H)

All the material, including source code, is made freely available for non-commercial use under the Creative Commons [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/legalcode) license. Feel free to use any of the material in your own work, as long as you give us appropriate credit by mentioning the title and author list of our paper.


## Datasets
We built our PG-GAN model from CelebA and CIFAR-10 dataset.   
CIFAR-10: https://www.cs.toronto.edu/~kriz/cifar.html   
CelebA: http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html  


## Results
The network would generate fake images during the training process, they are stored in /results directory.  
