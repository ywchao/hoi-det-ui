# HOI-Det-UI

Created by Yu-Wei Chao and Xieyang Liu, this is the UI for collecting the annotations in this paper:

**Learning to Detect Human-Object Interactions**  
Yu-Wei Chao, Yunfan Liu, Xieyang Liu, Huayi Zeng, Jia Deng  
IEEE Winter Conference on Applications of Computer Vision (WACV), 2018  

Check out the [project site](https://umich-ywchao-hico.github.io/) for more details.

### Citing HOI-Det-UI

Please cite HOI-Det-UI if it helps your research:

    @INPROCEEDINGS{chao:wacv2018,
      author = {Yu-Wei Chao and Yunfan Liu and Xieyang Liu and Huayi Zeng and Jia Deng},
      booktitle = {Proceedings of the IEEE Winter Conference on Applications of Computer Vision},
      title = {Learning to Detect Human-Object Interactions},
      year = {2018},
    }

### Demo

[Click here](https://umich-ywchao-hico.github.io/hoi-det-ui/demo_20171121.html) to experience the UI!

### Collecting Annotations on Amazon Mechanical Turk

We use [simple-amt](https://github.com/jcjohnson/simple-amt) as the backend for managing data anntation on AMT. To use this UI, simply copy `hico-det.html` to the directory `hit_templates` under `simple-amt`, and use it as the template when you launch HITs.
