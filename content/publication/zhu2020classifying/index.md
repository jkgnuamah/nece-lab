---
title: "Classifying Major Depressive Disorder Using fNIRS During Motor Rehabilitation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Yibo Zhu
- Jagadish Jayagopal
- Ranjana Mehta 
- Madhav Erraguntla
- Joseph Nuamah, 
- Anthony McDonald
- Heather Taylor
- Shuo-Hsiu Chang

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2020-02-07T00:00:00Z"
doi: "10.1109/TNSRE.2020.2972270"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-02-07T00:00:00Z" 

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Neural Systems and Rehabilitation Engineering*"
publication_short: ""

abstract: Major depressive disorder (MDD) has shown to negatively impact physical recovery in a variety of medical events (e.g., stroke and spinal cord injuries). Yet depression assessments, which are typically subjective in nature, are seldom considered to develop or guide rehabilitation strategies. The present study developed a predictive depression assessment technique using functional near-infrared spectroscopy (fNIRS) that can be rapidly integrated or performed concurrently with existing physical rehabilitation tasks. Thirty-one volunteers, including 14 adults clinically diagnosed with MDD and 17 healthy adults, participated in the study. Brain oxy-hemodynamic (HbO) responses were recorded using a 16-channel wearable continuous-wave fNIRS device while the volunteers performed the Grasp and Release Test in four 16-minute blocks. Ten features, extracted from HbO signals, from each channel served as inputs to XGBoost and Random Forest algorithms developed for each block and combination of successive blocks. Top 5 common features resulted in a classification accuracy of 92.6%, sensitivity of 84.8%, and specificity of 91.7% using the XGBoost classifier. This study identified mean HbO, full width half maximum and kurtosis, as specific neuromarkers, for predicting MDD across specific depression-related regions of interests (i.e., dorsolateral and ventrolateral prefrontal cortex). Our results suggest that a wearable fNIRS head probe monitoring specific brain regions, and limiting extraction to few features, can enable quick setup and rapid assessment of depression in patients. The overarching goal is to embed predictive neurotechnology during post-stroke and post-spinal-cord-injury rehabilitation sessions to monitor patients' depression symptomology so as to actively guide decisions about motor therapies.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
# - Source Themes
# featured: false

# Custom links (uncomment lines below)
# links:
# - name: HTML
#   url: https://www.tandfonline.com/doi/full/10.1080/24725838.2020.1855272?casa_token=168ZfRqGyj0AAAAA%3Ah0JV_DKzCQSRIgJwncol0jZkudpPmXXu6UZ7U12LUrVK6Pn-c61JtH5dCtYw1alGA2rlIsnr1sBFbQ

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
