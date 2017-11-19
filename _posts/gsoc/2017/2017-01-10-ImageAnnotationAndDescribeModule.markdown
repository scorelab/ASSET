---
layout: gsoc
categories: gsoc2017
divid: opendfimageanotation
title:  OpenDF - Image annotation and describe module
description: <p>When a disk image is being processed, the photo files will be piped to this module. This module should try to identify the contents of the image, try to annotate the objects and generate a description if can. Final goal of the module is to annotate and describe all the photos and store in Elasticsearch for easy searching.</p><p>This module will be on its own instance and should expose a RESTful API where OpenDF can interact with. You should finalize the module as a Docker images, where when spawned an instance, it should start all the needed services and be exposing the APIs.<p>Some links that might help you are,<br><a href="https://www.tensorflow.org/tutorials/image_recognition/" target="_blank">https://www.tensorflow.org/tutorials/image_recognition/</a><br><a href="https://research.googleblog.com/2016/09/show-and-tell-image-captioning-open.html" target="_blank">https://research.googleblog.com/2016/09/show-and-tell-image-captioning-open.html<br><a href="https://github.com/tensorflow/models/tree/master/im2txt" target="_blank">https://github.com/tensorflow/models/tree/master/im2txt</a><br>
githuburl: https://github.com/scorelab/OpenDF
requiredknowledge: Image processing, ML, TensorFlow, Python, RESTful services, Docker
possiblementors: Milindu Sanoj Kumarage(sanoj@scorelab.org)
---