---
title: 'YOLO-Z: Improving small object detection in YOLOv5 for autonomous vehicles'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Aduen Benjumea
  - admin
  - Fabio Cuzzolin
  - Andrew Bradley

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2021-12-22'
doi: '' # 2112.11798

# Schedule page publish date (NOT publication's date).
publishDate: '2021-12-22'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *International Confernce of Computer Vision (ICCV21)*
publication_short: In *ICCV21*

abstract: As autonomous vehicles and autonomous racing rise in popularity, so does the need for faster and more accurate detectors. While our naked eyes are able to extract contextual information almost instantly, even from far away, image resolution and computational resources limitations make detecting smaller objects (that is, objects that occupy a small pixel area in the input image) a genuinely challenging task for machines and a wide-open research field. This study explores how the popular YOLOv5 object detector can be modified to improve its performance in detecting smaller objects, with a particular application in autonomous racing. To achieve this, we investigate how replacing certain structural elements of the model (as well as their connections and other parameters) can affect performance and inference time. In doing so, we propose a series of models at different scales, which we name `YOLO-Z', and which display an improvement of up to 6.9% in mAP when detecting smaller objects at 50% IOU, at the cost of just a 3ms increase in inference time compared to the original YOLOv5. Our objective is to inform future research on the potential of adjusting a popular detector such as YOLOv5 to address specific tasks and provide insights on how specific changes can impact small object detection. Such findings, applied to the broader context of autonomous vehicles, could increase the amount of contextual information available to such systems.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2112.11798'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://drive.google.com/file/d/1qLATadudslhugc_J6ACq_5LHgzr2s90w/view?usp=share_link'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
