---
title: "Adaptive Equalized Multigroup Role Assignment in Ordered Subtasks[J]"
authors:
- Zhihang Yu
- Bo Wang, 
- Haibin Zhu, 
- Libo Zhang*
- date: "2025-06-03T00:00:00Z"
doi: "10.1109/TSMC.2024.3390138"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-05-06T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Systems, Man, and Cybernetics: Systems"
publication_short: ""

volume: "54"  # 卷号
issue: "8"    # 期号
pages: "5085 - 5098"  # 页码范围（可选

abstract: Role-based collaboration (RBC) is a new problem-solving paradigm that uses model environments-classes, agents, roles, groups, and objects (E-CARGO) to facilitate modeling. Task decomposition is widely adopted to reduce the difficulty of execution, resulting in multigroup collaboration problems. Multigroup role assignment (MGRA) has been proposed to solve the assignment of multiple groups. In many actual scenarios, there are dependencies between the decomposed subtasks, which is neglected by existing MGRA methods. Moreover, they disregard the fact that subtasks have diverse significance in the development of a project, which is of paramount importance to ensure the proper allocation of resources. To solve the complicated problem, the structured subtasks are formalized based on the emerging and promising RBC theory and E-CARGO model. Then, the assignment is abstracted into a complicated single-objective multiconstraint problem, named adaptive-equalized MGRA (AE-MGRA). In the formulated AE-MGRA problem, to improve the utilization of limited resources, the performance of each E-CARGO group needs to be equalized according to the corresponding subtask’s weight. As the optimal solution is difficult and time consuming to obtain, a tolerable deviation is utilized to achieve a near-optimal solution. Extensive experiments are conducted to sufficiently demonstrate the efficiency and stability of the proposed practical solution. In addition, the experimental results on static assignment and dynamic assignment further prove the effectiveness of the solution.



featured: false

links:
- name: Custom Link
  url: https://doi.org/10.1109/TSMC.2024.3390138


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
---