# CPThematicMaps
A dataset for multimodal tasks with annotated scientific figures of maps in climate science from publicly available, peer-reviewed scientific articles (CC BY-NC-SA 4.0). The figures in this dataset are of two types: **Thematic Map** with climatic parameters (themes) and **Other Map** (non-thematic map). The 'data' folder in this repository contains few data samples with the below naming conventions.
* **file name**: <article_doi>_<figure_reference>-<figure_context>.<file_extention>
* **figure context**: each figure has 5 files as per its <figure_context> field
  1) _annotation_ is the human annotation of figure type class (thematic or other map)
  2) _attribute_ is the generated attributes to label a figure content
  3) _caption_ is the caption of figure image
  4) _description_ is the generated description of figure image

FYI, the **full dataset will be disclosed post the paper review process**. It is currently privately hosted at HuggingFace Datasets. Meanwhile, please see the screenshot below to understand how users will see and access the full dataset post the paper review.
<img width="1957" height="1027" alt="Screenshot 2026-02-14 at 8 37 57 AM" src="https://github.com/user-attachments/assets/acbd6e2c-f1df-48e3-b496-c226e56da593" />
