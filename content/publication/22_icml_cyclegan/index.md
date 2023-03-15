---
title: 'Vision in adverse weather: Augmentation using CycleGANs with various object detectors for robust perception in autonomous racing'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Valentina Musat
  - Salman Khan
  - Alexander Rast
  - Fabio Cuzzolin
  - Andrew Bradley

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-07-22'
doi: '' # 2112.11798

# Schedule page publish date (NOT publication's date).
publishDate: '2022-07-22'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Safe Learning for Autonomous Driving Workshop at International Conference on Machine Learning (ICML22)*
publication_short: In *SL4AD @ ICML22*

abstract: In an autonomous driving system, perception - identification of features and objects from the environment - is crucial. In autonomous racing, high speeds and small margins demand rapid and accurate detection systems. During the race, the weather can change abruptly, causing significant degradation in perception, resulting in ineffective manoeuvres. In order to improve detection in adverse weather, deep-learning-based models typically require extensive datasets captured in such conditions - the collection of which is a tedious, laborious, and costly process. However, recent developments in CycleGAN architectures allow the synthesis of highly realistic scenes in multiple weather conditions. To this end, we introduce an approach of using synthesised adverse condition datasets in autonomous racing (generated using CycleGAN) to improve the performance of four out of five state-of-the-art detectors by an average of 42.7 and 4.4 mAP percentage points in the presence of night-time conditions and droplets, respectively. Furthermore, we present a comparative analysis of five object detectors - identifying the optimal pairing of detector and training data for use during autonomous racing in challenging conditions.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://learn-to-race.org/workshop-sl4ad-icml2022/assets/papers/paper_17.pdf'
url_code: ''
url_dataset: ''
url_poster: 'https://drive.google.com/file/d/1eVw4Y_DmCsFg7CiK4qgSv-uvvYaXqIQx/view?usp=share_link'
url_project: ''
url_slides: 'https://drive.google.com/file/d/1WlL3gsweF2WSrkjaZdFgAuvVnT4vrbs4/view?usp=share_link'
url_source: ''
url_video: 'https://drive.google.com/file/d/1O7RyzCAihRxE8ilXs5YZCMX44jhY0Ysz/view?usp=share_link'

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
