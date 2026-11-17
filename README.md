## Evaluating the Robustness of Multimodal Early Fusion for Fake News Detection under Missing Modalities

As there is a lot of misinformation on the internet caused mainly due to increasingly use of multi-model
content generation using text and images. This paper will investigate the robustness of a multimodal Early Fusion
model for fake news detection when either text or image information becomes unavailable. We used Fakeddit dataset
to implement and check how the model performs. These 5 levels of missingness were evaluated: 10%, 30%, 50%, 70%
and 100%. Text and image features were embedded using pretrained models as Bert and Resnet50 respectively. The
performance was evaluated in a controlled environment using metrics such as Accuracy, Precision, Recall, F1-score
and ROC-AUC. Under complete image-feature removal, performance remained comparatively stable with the accuracy
going from 80.93% to 78.18%, whereas complete text-feature removal reduced the accuracy from 80.93% to 69.55% .
This suggests the model relies more heavily on textual features for its predictions. Therefore, the model exhibits greater
dependence on textual information than visual information.
