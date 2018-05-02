In this paper, we propose a new dataset and benchmark for low altitude UAV object detection, aiming to find and localize waste plastic bottles in the wild, as well as to inspire the development of object detection models to be capable of detecting small and transparent objects. To this end, we collect 25,407 UAV images of bottles with various kinds of backgrounds. Unlike traditional horizontal bounding box based annotation methods, we use the oriented bounding box to accurately and compactly annotate the bottles, which provides more detailed information for subsequent robotic grasping. The fully annotated images contain 34,791 bottles, each of which is annotated by an arbitrary (5 d.o.f.) quadrilateral. To build a baseline for bottle detection, we evaluate several state-of-the-art object detection algorithms on our UAV-Bottle Dataset (UAV-BD), such as Faster R-CNN, SSD, YOLOv2 and RRPN. We also present an analysis of the dataset along with baseline approaches. Both the dataset and benchmark are made publicly available to the vision community on our website to advance research in the area of object detection from UAVs.

## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/jwwangchn/UAV-BD/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/jwwangchn/UAV-BD/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
