# Image-Captioning-with-Translation-using-Attention-Mechanism
Automatic Image captioning suggests that the generation of a caption
for a picture by a machine. Image captioning is performed by feting objects, attributes and
affiliation between them. During this paper, we tend to introduce associate degree accommodative attention encoderdecoder frame which may mechanically decide once to calculate on visual signals and once to only calculate on the language model. Of course, once hoping on visual signals, the model
additionally decides wherever – that image region – it ought to attend to. In such a frame for
image captioning, a picture is initial decoded to a collection of purpose vectors via a CNN
grounded network associate degreed additionally decrypted to words via an RNN grounded
network, wherever the eye medium attendants the decipherment method by generating a
weighted traditional over the uprooted purpose vectors for every time step. 

# Datasets
There are various datasets available for image captioning varying in terms of number of
images and their attributes. 
<ul>
<li> MS COCO Dataset: 300k images, nearby 2 million objects, 80 different categories of
  objects, and 05 captions for each image.</li>
<li> Flickr30K Dataset: 30k images with 158k annotators.</li>
<li> Flickr8K Dataset: 8K images, 6k for training and rest 2k for testing and validation.</li>
<li> MIT-Adobe 5k Dataset: Dataset consists of 5,000 images. This dataset contains various
kinds of images based on different subjects, scenes, conditions, lighting etc.</li>
<li> FlickrStyle10K Dataset: This dataset has 10k images with stylized captions. Among
these, there are 7k training images, 2k for testing and 1k for validation purpose. The
images are based on romantic, humorous and some factual scenes. </li>
</ul>

# Performance Metrics
<ul>
<li> BLEU: The metric is Bilingual evaluation understudy that compares the generated
caption with referenced caption and word to word matching takes place. On an
average score is computed. However, syntactical correctness is not measured here.</li>
<li> Generated Text: This is for test Reference Text: This is only test (score 0.75 or 75%)
BLUE-1 matches word to word. Similarly, we have BLUE-2, BLUE-3, BLUE-4 evaluation
metrics for pair wise matching.</li>
<li> ROUGE: The metric is Recall-Oriented Understudy for Gisting Evaluation that
measures the quality of textual summaries.</li>
<li> METEOR: It is Metric for Evaluation of Translation with Explicit Ordering and is useful
to measure stems of a sentence and synonym for words. This is a better approach to
make a better correlation at the sentence or the segment level. </li>
</ul>


Clone the project from the given link: https://drive.google.com/drive/folders/1maI9b8bSExOPqGOSsrnogZBAiyPGtfd4?usp=sharing
