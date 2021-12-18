---
title: "LAVA: Fine-Grained 3D Indoor Wireless Coverage for Small IoT Devices"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- R. Ivan Zelaya
- admin
- Jeremy Gummeson
- Kyle Jamieson
- Wenjun Hu

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

# date: "2013-07-01T00:00:00Z"
doi: "10.1145/3452296.3472890"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In In Proceedings of the 2021 ACM SIGCOMM 2021 Conference
publication_short: In SIGCOMM '21

abstract: Small IoT devices deployed in challenging locations suffer from uneven 3D coverage in complex environments. This work optimizes indoor coverage with LAVA, a Large Array of Vanilla Amplifiers. LAVA is a standard-agnostic cooperative mesh of elements, i.e., RF devices each consisting of several switched input and output antennas connected to fixed-gain amplifiers. Each LAVA element is further equipped with rudimentary power sensing to detect nearby transmissions. The elements report power readings to the LAVA control plane, which then infers active link sessions without explicitly interacting with the endpoint transmitter or receiver. With simple on-off control of amplifiers and antenna switching, LAVA boosts passing signals via multi hop amplify-and-forward. LAVA explores a middle ground between smart surfaces and physical-layer relays. Multi-hopping over short inter-hop distances exerts more control over the end-to-end trajectory, supporting fine-grained coverage and spatial reuse. Ceiling testbed results show throughput improvements to individual Wi-Fi links by 50% on average and up to 100% at 15 dBm transmit power (193% on average, up to 8x at 0 dBm). ZigBee links see up to 17 dB power gain. For pairs of co-channel concurrent links, LAVA provides average per-link throughput improvements of 517% at 0 dBm and 80% at 15 dBm.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

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
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
<!-- 
{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
 -->