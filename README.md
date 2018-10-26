# Notes on face detection, verification and recognition

- FaceNet
  - [FaceNet: A Unified Embedding for Face Recognition and Clustering](https://arxiv.org/abs/1503.03832)
    - Use of triplet loss as ConvNet loss function
    - Face embeddings, that map faces as feature vectores. Easy to compare and measure similarity.
    - LFW dataset accuracy = 99.63%. YouTube Faces DB = 95.12%.

  - Triplet loss
     - [Triplet Loss - Special applications: Face recognition & Neural style transfer | Coursera](https://www.coursera.org/lecture/convolutional-neural-networks/triplet-loss-HuUtN)
     - [Triplet Loss and Online Triplet Mining in TensorFlow](https://omoindrot.github.io/triplet-loss)

  - OpenFace
    - Python and Torch implementation of face recognition based on FaceNet
    - [Implementation of face recognition with deep neural networks](https://cmusatyalab.github.io/openface/#openface)

  - Comparing embeddings
    - [Comparing embeddings, FaceNet, euclidean distance between embeddings](https://www.python36.com/face-detection-matching-using-facenet/)

- Facial landmark detection
  - [One Millisecond Face Alignment with an Ensemble of Regression Trees](http://www.csc.kth.se/~vahidk/papers/KazemiCVPR14.pdf)

- Ageing, adding features, beards etc.
  - [Deep Feature Interpolation (CVPR 2017)](https://www.cs.cornell.edu/projects/dfi/) [github](https://github.com/paulu/deepfeatinterp)

- Frontalization
  - [Effective Face Frontalization in Unconstrained Images](https://talhassner.github.io/home/publication/2015_CVPR_1)
