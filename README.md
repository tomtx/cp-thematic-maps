# CPThematicMaps
A dataset for multimodal tasks with annotated scientific figures of maps in climate science from publicly available, peer-reviewed scientific articles (CC BY-NC-SA 4.0). The figures in this dataset are of two types: **Thematic Map** with climatic parameters (themes) and **Other Map** (non-thematic map). The map figures are annotated with eight classes of themes, specifically a) atmospheric pressure, b) evaporation, c) humidity, d) precipitation, e) radiation, f) temperature, and g) wind or h) none. The 'data' folder in this repository contains some samples of figures with the below naming conventions.
* **figure file name**: [article_doi]_[figure_reference]-[figure_content].[file_extention]
* **figure file content**: each figure has 6 files as per the [figure_content] field in the file name
  1) _annotation_ is the human annotation of the figure type class (labels are multiple themes per each map figure)
  2) _attribute_ is the generated label for generated visual attributes in the figure (metadata.json shows attribute names for attribute IDs)
  3) _caption_ is the caption of the figure image from its article
  4) _description_ is the generated description of the figure image
  5) _discourse_ is the scientific discourse in the article about the figure
  6) _image_ is the image of the figure from its article

FYI, the **full dataset will be disclosed post the paper review** process. It is currently privately hosted at Hugging Face Datasets. Meanwhile, please see the screenshot below to understand how users will see and access the full dataset post the paper review.

<img width="1670" height="1134" alt="Screenshot 2026-02-15 at 3 50 52 PM" src="https://github.com/user-attachments/assets/89d645fe-158a-4b88-83e7-227b8224b156" />
