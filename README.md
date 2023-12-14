**Note: Please be advised that we intend to modify the repository name from "Visual Goal-Step Inference" to "Visual Goal Guidance." However, as the link has already been shared, we will proceed with the current name**

***Visual Goal-Guidance: Step Inference for Instruction Retrieval***

Description: Given a text-based goal and a set of images, the idea is to retrieve all the images that corresponding to the steps leading up to the goal and eventually order them in the next best action based order.

Our primary implementation is predominantly encapsulated in the following notebooks: "Goal_step_relevance_LLava.ipynb," "Intent_data_prep_for_step_ordering," and "Step_ordering.ipynb." 

In our exploration, we employed various models, including ViT and CLIP. Subsequently, we progressed towards an end-to-end trained large multimodal model that integrates a vision encoder and Vicuna for comprehensive visual and language understanding purposes.

Remarkably, we achieved commendable performance without the necessity for prior training with a smaller model in comparison with the custom model integration with LLM and CLIP using Microsoft GIT. It is important to acknowledge the challenges associated with intent detection from images, such as discerning between visually similar objects like celery, scallion, and asparagus.

