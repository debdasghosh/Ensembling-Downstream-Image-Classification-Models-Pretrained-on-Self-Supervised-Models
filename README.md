# Ensembling-Downstream-Image-Classification-Models-Pretrained-on-Self-Supervised-Models
Ensembling Downstream Image Classification Models Pretrained on Self-Supervised Models

### (1) Ensembling makes sense if the models are trying to solve the same problem. Is that the case?

#### Yes, our downstream task will be solving the problem of classifying images from the ImageNet dataset


### (2) Ensembling and pre-training seem like orthogonal directions of progress/improvement. Am I missing something?

#### Our initial hypothesis is that they would be complementary, but we hadn't thought deeply on this yet. We could certainly run some ablation studies to test this hypothesis.


### (3) Will pre-training enhance the diversity of the ensembled models?

#### Our hypothesis is yes since each model in the ensemble will be pretrained on a different pretext task and/or dataset. Again we could tease this out through ablation studies.
