<div align="center">
<img src="./assets/icon.jpg" width = "200" >
</div>
<div align="center">
An introduction to AI methods for flying agents (birds, UAVs, etc.)
</div>

## :bird: Bird flock
* (*Nature communication*) Behavioural plasticity and the transition to order in jackdaw flocks. [[paper]](https://www.nature.com/articles/s41467-019-13281-4)
* (*Nature ecology & evolution*) Costs and benefits of social relationships in the collective motion of bird flocks. [[paper]](https://www.nature.com/articles/s41559-019-0891-5)

## 📓 Related works
### 👬 Multi-object tracking
* (2023 CVPR) Tracking Multiple Deformable Objects in Egocentric Videos. [[paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Huang_Tracking_Multiple_Deformable_Objects_in_Egocentric_Videos_CVPR_2023_paper.html)[[project]](https://mingzhenhuang.com/projects/detracker.html)
> New task: track multiple deformable objects using smart glasses. \
> New dataset: DogThruGlasses, 150 videos and 73K annotated frames from smart glasses.
> ✨: Treat a new task from specific to general, while write a paper in an opposite way.

* (2023 CVPR) Referring Multi-Object Tracking. [[paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Wu_Referring_Multi-Object_Tracking_CVPR_2023_paper.html)[[project]](https://referringmot.github.io)
> New task: employ a language expression as a semantic cue to track specific objects. \
> New dataset: Refer-KITTI, 18 videos with 818 expressions
> ✨: multi-model, visual-language.

* (2023 CVPR) MotionTrack: Learning Robust Short-term and Long-term Motions for Multi-Object Tracking. [[paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Qin_MotionTrack_Learning_Robust_Short-Term_and_Long-Term_Motions_for_Multi-Object_Tracking_CVPR_2023_paper.pdf)
> Task: associate detected objects between frames by modeling object motion with attention.  \
> ✨: embedding object motion into latent space.

* (2023 arxiv) SparseTrack: Multi-Object Tracking by Performing Scene Decomposition based on Pseudo-Depth. [[paper]](https://arxiv.org/pdf/2306.05238.pdf)[[project]](https://github.com/hustvl/SparseTrack)
> Task: associate detected objects between frames by pseodo-depth. \
> ✨: rseodo-depth ordering.

### 🏃 Point tracking and others

* (2023 arxiv) Tracking Everything Everywhere All at Once. [[paper]](https://arxiv.org/abs/2306.05422)[[project]](https://omnimotion.github.io/)
> New task: estimate dense and long-range motion from a video sequence during inference. \
> ✨: a canonical 3D volume to represent 2D video.

* (2020 NeurIPS) Space-Time Correspondence as a Contrastive Random Walk. [[paper]](https://proceedings.neurips.cc/paper/2020/hash/e2ef524fbf3d9fe611d5a8e90fefdc9c-Abstract.html)[[project]](https://ajabri.github.io/videowalk/)
> Task: obtain the correspondence of image patches by unsupervised learning from a palindrome sequence, where the query and target are the same. \
> ✨: Unsupervised learning from a palindrome sequence. 

## 📽️ Recommended resources
<!-- Parts of this work include video footage from links below, which have been used for academic purposes. We would like to acknowledge and thank the authors for providing these valuable resources -->
* [Earthflight](https://www.amazon.co.uk/Earth-Flight-Season-1/dp/B00HXENBQG) -- BBC, 2011, 6 episodes.
> "A British nature documentary that shows a flight from the view of the wings of birds across six continents, showing some of the world's greatest natural spectacles from a bird's-eye view. The BBC series was created by John Downer and narrated by David Tennant and consisted of six 60-minute episodes. The first episode aired on BBC One on 29 December 2011." -- from [Wikipedia](https://en.wikipedia.org/wiki/Earthflight)
* [IOC World Bird List](https://www.worldbirdnames.org/new/) -- International Ornithological Congress, updating
> "The IOC World Bird List is an open access resource of the international community of ornithologists. Our primary goal is to facilitate worldwide communication in ornithology and conservation based on an up-to-date evolutionary classification of world birds and a set of English names that follow explicit guidelines for spelling and construction." --from [IOC World Bird List](https://www.worldbirdnames.org/new/)