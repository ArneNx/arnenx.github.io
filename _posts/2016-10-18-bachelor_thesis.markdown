---
title:  "Alignment Methods for Attention-based Neural Machine Translation"
date:   2016-10-18 15:20:23
categories: [machine_learning]
tags: [machine translation, machine learning, deep learning]
---
The attention-based neural machine translation (NMT) approach has outperformed traditional phrase based approaches on numerous translation tasks in recent evaluations. Attention-based NMT uses an end-to-end trainable artificial neural network (ANN) to produce the translation for a given sentence. As a part of the translation, the ANN implicitly produces a weighting over the words of the source sentence, which can be interpreted as a soft alignment from source to target sentence.

![The target foresight approach]({{ site.baseurl }}{% link /images/target_foresight.png %})

In this bachelor thesis, the attention mechanism and the resulting alignments are examined. An evaluation is conducted that shows a clear correlation between the alignment score produced by traditional and recently proposed alignment evaluation methods with the translation quality. Moreover, in a comparison of NMT alignments with state-of-the-art statistical alignments, we can see that the soft alignments the NMT approach produces offer room for improvement. Also, the experiments indicated that the attention-based alignments have a significant impact on the translation quality. Hence, we propose multiple approaches to extend and improve the attention mechanism and thereby the alignment as well as the translation quality. Among these are two methods that resulted in an improvement of more than one BLEU %.

Additionally, we also modified the attention-based NMT model to generate alignments for given source and target sentence pairs. With this model, we were able to halve the AER and SAER scores, compared to the standard NMT attention model, and outperform state-of-the-art alignments produced by traditional statistical alignment models.

Read the [paper](https://ufal.mff.cuni.cz/pbml/108/art-peter-nix-ney.pdf) on the target foresight approach \\
Read the [full thesis]({{ site.baseurl }}{% link /assets/bachelor_thesis.pdf %}) \\
See the [presentation slides]({{ site.baseurl }}{% link /assets/bachelor_final_talk.pdf %})
