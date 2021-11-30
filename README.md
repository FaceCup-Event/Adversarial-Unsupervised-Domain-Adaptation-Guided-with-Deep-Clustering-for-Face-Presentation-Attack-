# Adversarial-Unsupervised-Domain-Adaptation-Guided-with-Deep-Clustering-for-Face-Presentation-Attack-
![image](https://user-images.githubusercontent.com/94538977/144032989-9673277e-0cbb-4816-acc8-85fa49e71ab5.png)


Face Presentation Attack Detection (PAD) has drawn increasing attentions to secure the face recognition systems that are widely used in many applications. Conventional face anti-spoofing methods have been proposed,
assuming that testing is from the same domain used for training, and so cannot generalize well on unseen
attack scenarios. The trained models tend to overfit to the acquisition sensors and attack types available in
the training data. In light of this, we propose an end-to-end learning framework based on Domain Adaptation
(DA) to improve PAD generalization capability. Labeled source-domain samples are used to train the feature
extractor and classifier via cross-entropy loss, while unsupervised data from the target domain are utilized in
adversarial DA approach causing the model to learn domain-invariant features. Using DA alone in face PAD
fails to adapt well to target domain that is acquired in different conditions with different devices and attack
types than the source domain. And so, in order to keep the intrinsic properties of the target domain, deep clustering of target samples is performed. Training and deep clustering are performed end-to-end, and experiments
performed on several public benchmark datasets validate that our proposed Deep Clustering guided Unsupervised Domain Adaptation (DCDA) can learn more generalized information compared with the state-of-the-art
classification error on the target domain.
