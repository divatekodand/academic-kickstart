+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.

title = "Projects"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.
[[experience]]
  title = "SerFer: Serverless Inference of Machine Learning Models"
  company = "PDF"
  company_url = ""
  location = ""
  date_start = "2019-01-01"
  date_end = "2019-05-10"
  description = """SerFer is a framework for serving Deep Learning queries built on top on Serverless Computing Platform (AWS Lambda). It distributes the computation across several lambda functions by splitting both the Deep Learning Model, as well as the input query.
  """

[[experience]]
  title = "Word Embeddings for Fine Grained Sentiment Analysis"
  company = "PDF"
  company_url = "files/word_embeddings.pdf"
  location = ""
  date_start = "2018-09-01"
  date_end = "2018-11-30"
  description = """Current methods to learn word embeddings result in similar representations for words with different connotations and hence, sentiment recognition systems relying on them perform poorly. To overcome this, I proposed a new approach to learn word representations, which improves the performance of sentiment recognition systems that rely on word vector representations.  """

[[experience]]
  title = "Reconfigurable Architecture for Face Detection"
  company = "PDF"
  company_url = "files/face_detection.pdf"
  location = ""
  date_start = "2015-08-01"
  date_end = "2016-04-20"
  description = """ 

  * Developed a custom Face Detection Model suitable for hardware implementation using Viola-Jones Face Detection Framework. This model was trained and validated on MATLAB.
  * Designed and developed hardware accelerator for face detection using Xilinx Zedboard.
  * Languages and Tools used - Xilinx Vivado Design suite, C++, VHDL, and OpenCV.
  """

[[experience]]
  title = "Algebraic Reconstruction using SART and Total Variation De-noising"
  company = "PDF"
  company_url = "files/sart_proj.pdf"
  location = ""
  date_start = "2015-01-01"
  date_end = "2015-04-01"
  description = """ 

  * Developed and implemented an improved version of SART Algorithm (simultaneous algebraic reconstruction technique, a computerized tomography algorithm) that uses total variation denoising to reduce noise levels in the images reconstructed from limited CT projection data.
  """

+++
