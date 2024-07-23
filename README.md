# SkinLiTE: Lightweight Supervised Contrastive Learning Model for Enhanced Skin Lesion Detection and Disease Typification in Dermoscopic Images

DOI: ([10.2174/0115734056313837240612065845](http://dx.doi.org/10.2174/0115734056313837240612065845))

![Graphical Abstract](https://github.com/SalhaAlzahrani/SkinLiTE/blob/main/Graphical%20Abstract.png)

****
Abstract

Introduction: This study introduces SkinLiTE, a lightweight supervised contrastive learning model tailored to enhance the detection and typification of skin lesions in dermoscopic images. The core of SkinLiTE lies in its unique integration of supervised and contrastive learning approaches, which leverages labeled data to learn generalizable representations. This approach is particularly adept at handling the challenge of complexities and imbalances inherent in skin lesion datasets.

Model: The methodology encompasses a two-phase learning process. In the first phase, SkinLiTE utilizes an encoder network and a projection head to transform and project dermoscopic images into a feature space where contrastive loss is applied, focusing on minimizing intra-class variations while maximizing inter-class differences. The second phase freezes the encoder's weights, leveraging the learned representations for classification through a series of dense and dropout layers. The model was evaluated using three datasets from Skin Cancer ISIC 2019-2020, covering a wide range of skin conditions.

![Graphical Abstract](https://github.com/SalhaAlzahrani/SkinLiTE/blob/main/Model.png)

Results: SkinLiTE demonstrated superior performance across various metrics, including accuracy, AUC, and F1 scores, particularly when compared with traditional supervised learning models. Notably, SkinLiTE achieved an accuracy of 0.9087 using AugMix augmentation for binary classification of skin lesions. It also showed comparable results with the state-of-the-art approaches of ISIC challenge without relying on external data, underscoring its efficacy and efficiency. The results highlight the potential of SkinLiTE as a significant step forward in the field of dermatological AI, offering a robust, efficient, and accurate tool for skin lesion detection and classification. Its lightweight architecture and ability to handle imbalanced datasets make it particularly suited for integration into Internet of Medical Things environments, paving the way for enhanced remote patient monitoring and diagnostic capabilities.

Conclusion: This research contributes to the evolving landscape of AI in healthcare, demonstrating the impact of innovative learning methodologies in medical image analysis.

