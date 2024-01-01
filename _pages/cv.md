---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Computer Science and Information Engineering, National Taiwan University, 2022
* M.S. in Computer and Information Science, University of California - Los Angeles, 2024 (expected)

Experience
======
* *Data Engineer Intern* \| **Graphen, Inc.**, Taipei, Dec. 2021 - Nov. 2022
  * Addressed fisheye camera distortion by developing ROS packages with OpenCV, leveraging the fisheye camera's broader view to improve the accuracy of obstacle detection.
  * Configured the ROS docker environment and conducted robot simulation with TurtleBot3 SLAM and Gazebo to assess the applicability of the auto-tracking algorithm.
  * Developed C++ scripts to extract the robot pose from SLAM and made a progress in the auto-docking implementation.
  * Optimized YoloV4 models to achieve 95% precision and establish the pipeline integration with EacyOCR for license plate recognition.
  * Converted the YoloV4 model into ONNX format to promote compatibility between various deep learning frameworks, making the model capable of PyTorch.
* *Web Development Engineer* \| **BizPro**, Taipei, Sep. 2022 - Feb. 2023
  * Crawled the membership data with PyMongo and efficiently resolved data format inconsistency by leveraging SQL and Python skills.
  * Developed the back-end system with Node.js and MongoDB; crafted efficient APIs for search, filter, and database management functionalities.
  * Developed an intuitive UI for the back-end system, empowering non-coders to efficiently manage and maintain the system, enhancing user experience and operational efficiency.
* *Undergraduate Research Assistant* \| **AI^2 Lab**, Taipei, Dec. 2021 - Aug. 2022
  * Collaborated with two researchers to survey training-free Network Architecture Search (NAS) methods and designed experiments on Zen-NAS.
  * Adapted the NAS-Bench-201 API to conduct testing of Zen-NAS within the NAS-Bench-201 search space and analyzed the impact on different search spaces.
  * Utilized PyTorch and Numpy to replace random image input with the Cifar dataset and improved the top-1 accuracy on the Cifar100 dataset from 80.05% to 81.60% in Zen-NAS.

Skills
======
* **Programming Language:** *C, C++, Java, Python, SQL, Shell, Swift*
* **Network & Web:** *JavaScript, Node.js, Socket Programming, DNS, WireShark, Web Crawling, MongoDB*
* **Develop Tools:** *Git, Docker, VMware Fusion*
* **Machine Learning:** *PyTorch, TensorFlow, Yolo, Network Architecture Search (NAS)*
* **Robotics:** *Robot Operating System (ROS), Gazebo, SLAM*

Coarsework
======
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
