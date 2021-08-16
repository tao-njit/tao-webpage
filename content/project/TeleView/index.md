---
title: TeleView
summary: Design and develop ubiquitous machine vision with adaptive wireless networking and edge computing.
<!-- tags:
- Deep Learning -->
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Overview of UbiVision System
  focal_point: Smart

-- links:
# - icon: twitter
  # icon_pack: fab
  # name: Follow
  # url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: "" 

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
<!-- slides: example -->
---

This project aims to realize an ambitious goal: ubiquitous machine vision (UbiVision) whose ultimate objective is to provide a platform that enables people from all over the world to share their smart cameras, which can be Uber, Airbnb, or Mobike in the context of smart cameras. For example, a person in New York City can “see” what is happening in Los Angeles via a wearable camera shared by another person located in Los Angeles. However, sharing the scenes captured by cameras directly will incur serious privacy issues. Moreover, the raw visual data may result in excessive traffic loads that congest the network and downgrade the system performance. To preserve privacy and reduce traffic loads, UbiVision performs visual data analysis on smart cameras and edge servers, which allows its customers to only share information extracted from camera scenes, e.g., how many people are queuing outside an Apple store for a new iPhone, or selected objects in the scene, e.g., a vagrant husky for the purpose of the lost and found. This project studies enabling technologies for realizing UbiVision. The UbiVision framework consists of three main research tasks. In this framework, smart cameras, radio access networks, and edge servers are recognized as infrastructure that can support multiple machine vision services through adaptive end-to-end multi-domain resource orchestration. The PIs envision that a machine vision service provider (MVSP) will own and manage a virtual network consisting of a radio access network and edge servers and have the access to ubiquitous cameras via camera sharing agreements with camera owners. Under this scenario, MVSPs are challenged to dynamically manage highly coupled resources and functions across multiple technology domains: 1) camera functions such as image preprocessing and embedded machine vision; 2) network resources in the radio access network; 3) computation resources and machine vision on the edge servers. To solve the problem, the PIs propose an interdisciplinary research project which integrates techniques and perspectives from wireless networking, computer vision, and edge computing in designing and optimizing UbiVision.


<!-- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum. Sed ac faucibus dolor, scelerisque sollicitudin nisi. Cras purus urna, suscipit quis sapien eu, pulvinar tempor diam. Quisque risus orci, mollis id ante sit amet, gravida egestas nisl. Sed ac tempus magna. Proin in dui enim. Donec condimentum, sem id dapibus fringilla, tellus enim condimentum arcu, nec volutpat est felis vel metus. Vestibulum sit amet erat at nulla eleifend gravida.

Nullam vel molestie justo. Curabitur vitae efficitur leo. In hac habitasse platea dictumst. Sed pulvinar mauris dui, eget varius purus congue ac. Nulla euismod, lorem vel elementum dapibus, nunc justo porta mi, sed tempus est est vel tellus. Nam et enim eleifend, laoreet sem sit amet, elementum sem. Morbi ut leo congue, maximus velit ut, finibus arcu. In et libero cursus, rutrum risus non, molestie leo. Nullam congue quam et volutpat malesuada. Sed risus tortor, pulvinar et dictum nec, sodales non mi. Phasellus lacinia commodo laoreet. Nam mollis, erat in feugiat consectetur, purus eros egestas tellus, in auctor urna odio at nibh. Mauris imperdiet nisi ac magna convallis, at rhoncus ligula cursus.

Cras aliquam rhoncus ipsum, in hendrerit nunc mattis vitae. Duis vitae efficitur metus, ac tempus leo. Cras nec fringilla lacus. Quisque sit amet risus at ipsum pharetra commodo. Sed aliquam mauris at consequat eleifend. Praesent porta, augue sed viverra bibendum, neque ante euismod ante, in vehicula justo lorem ac eros. Suspendisse augue libero, venenatis eget tincidunt ut, malesuada at lorem. Donec vitae bibendum arcu. Aenean maximus nulla non pretium iaculis. Quisque imperdiet, nulla in pulvinar aliquet, velit quam ultrices quam, sit amet fringilla leo sem vel nunc. Mauris in lacinia lacus.

Suspendisse a tincidunt lacus. Curabitur at urna sagittis, dictum ante sit amet, euismod magna. Sed rutrum massa id tortor commodo, vitae elementum turpis tempus. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean purus turpis, venenatis a ullamcorper nec, tincidunt et massa. Integer posuere quam rutrum arcu vehicula imperdiet. Mauris ullamcorper quam vitae purus congue, quis euismod magna eleifend. Vestibulum semper vel augue eget tincidunt. Fusce eget justo sodales, dapibus odio eu, ultrices lorem. Duis condimentum lorem id eros commodo, in facilisis mauris scelerisque. Morbi sed auctor leo. Nullam volutpat a lacus quis pharetra. Nulla congue rutrum magna a ornare.

Aliquam in turpis accumsan, malesuada nibh ut, hendrerit justo. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Quisque sed erat nec justo posuere suscipit. Donec ut efficitur arcu, in malesuada neque. Nunc dignissim nisl massa, id vulputate nunc pretium nec. Quisque eget urna in risus suscipit ultricies. Pellentesque odio odio, tincidunt in eleifend sed, posuere a diam. Nam gravida nisl convallis semper elementum. Morbi vitae felis faucibus, vulputate orci placerat, aliquet nisi. Aliquam erat volutpat. Maecenas sagittis pulvinar purus, sed porta quam laoreet at. -->
