# Deep Learning Models Compression for Agricultural Plants
This is set of easy to use colab notebooks the paper
[Fountsop, Arnauld Nzegha, Jean Louis Ebongue Kedieng Fendji, and Marcellin Atemkeng. "Deep Learning Models Compression for Agricultural Plants." Applied Sciences 10.19 (2020): 6866.](https://www.mdpi.com/2076-3417/10/19/6866/pdf)



Deep learning has been successfully showing promising results in plant disease detection,
fruit counting, yield estimation, and gaining an increasing interest in agriculture. Deep learning
models are generally based on several millions of parameters that generate exceptionally large
weight matrices. The latter requires large memory and computational power for training, testing,
and deploying. Unfortunately, these requirements make it difficult to deploy on low-cost devices
with limited resources that are present at the fieldwork. In addition, the lack or the bad quality
of connectivity in farms does not allow remote computation. An approach that has been used to
save memory and speed up the processing is to compress the models. In this work, we tackle the
challenges related to the resource limitation by compressing some state-of-the-art models very often
used in image classification. For this we apply model pruning and quantization to LeNet5, VGG16,
and AlexNet. Original and compressed models were applied to the benchmark of plant seedling
classification (V2 Plant Seedlings Dataset) and Flavia database. Results reveal that it is possible to
compress the size of these models by a factor of 38 and to reduce the FLOPs of VGG16 by a factor of
99 without considerable loss of accuracy.
