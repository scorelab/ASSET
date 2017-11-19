---
layout: gsoc
categories: gsoc2017
divid: opendfacerecognition
title:  OpenDF - Face recognition and profiles module
description: <p>When a disk image is being processed, the photo files will be piped to this module. This module should try to identify the face on the images, try to annotate the faces. Module should maintain a database of identified faces as profiles, thus, all the images of the same person should be categorized under one profile. Users should be able to manage names and other details of the profiles on this database. When asked for images of a particular person, given a name or any other available detail, this module should suggest matching profiles. Given an image, this module should suggest matching profiles by identifying the face on the given image.</p><p>This module will be on its own instance and should expose a RESTful API where OpenDF can interact with. You should finalize the module as a Docker images, where when spawned an instance, it should start all the needed services and be exposing the APIs<p>Some links that might help you are,<br><a href="https://github.com/davidsandberg/facenet" target="_blank">https://github.com/davidsandberg/facenet</a>
githuburl: https://github.com/scorelab/OpenDF
requiredknowledge: Image processing, ML, TensorFlow, Python, RESTful services, Docker
possiblementors: Milindu Sanoj Kumarage(sanoj@scorelab.org)
---