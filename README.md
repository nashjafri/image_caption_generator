<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1GKssGKoEquFt-5UQ3aRkl_1MrvxeWIu7" alt="Project Logo" width="200"/>
</p>

<h1 align="center">Image Caption Generator</h1>
<p align="center"><b>Erdős Deep Learning Bootcamp – Fall 2025</b></p>
<p align="center"><i>
Team: <a href="https://github.com/keshavdahiya">Keshav Dahiya</a>, 
<a href="https://github.com/nashjafri">Nasheed Jafri</a>
</i></p>
**Project Description:** This project aims to build an image captioning system that generates fluent and semantically accurate descriptions of images. Initially, we will briefly explore pre-trained captioning models to understand their working and use them as baselines. Our primary focus is to develop image captioning models from scratch. We will begin with simple encoder-decoder architectures (CNN + RNN/LSTM) and progress toward Transformer-based models, scaling from Flickr8k to Flickr30k to MS COCO datasets.

Model evaluation will rely on standard captioning metrics (CIDEr, SPICE, BLEU, METEOR, ROUGE) along with semantic similarity measures (CLIPScore, BERTScore). Small-scale human evaluation will supplement automated metrics to assess fluency and relevance.

**Dataset Description:**
- [Flickr8k](https://www.kaggle.com/datasets/adityajn105/flickr8k): 8,000 images with 5 captions each; good for prototyping and debugging quickly.
- [Flickr30k](https://www.kaggle.com/datasets/adityajn105/flickr30k): 31,000 images with 5 captions each; larger and more diverse.
- [MS COCO](https://cocodataset.org/#home): 120,000 training images with 5 captions each; the main benchmark dataset for image captioning tasks.

**Key Performance Indicators:**
- CIDEr Score: Primary benchmark metric for captioning quality. 
- SPICE Score: Measures semantic correctness of captions. 
- BLEU-4 and METEOR: N-gram overlap metrics for comparison with prior work. 
- CLIPScore: Image-text embedding similarity to reduce hallucinations.
- BERTScore: Semantic similarity metric that compares generated captions with references using contextual embeddings beyond exact word matches.

**Stakeholders:**
- Assistive Technology Developers: Companies and nonprofits creating tools for visually impaired users that need accurate image descriptions.
- Tech Companies with Search and Recommendation Systems: Companies that rely on image-text alignment for search, ads, and recommendations.
- E-commerce Platforms: Companies that need automatic captions to improve product discovery and accessibility.
- Content Moderation and Media Platforms: Social networks and news aggregators that use captioning to detect, describe, and categorize uploaded images.

**Future Goal:** Extend the project to real-time video captioning for short video clips, moving from single-image descriptions to continuous temporal narratives.
