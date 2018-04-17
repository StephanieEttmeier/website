+++
title = "Predicting thermal reference conditions for USA streams and rivers"
date = "2013-03-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Ryan A. Hill**" , "Charles P. Hawkins", "Daren M. Carlisle"]


# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "*Freshwater Science* 32: 39-55"
#publication_short = "In *FWS*"

# Abstract and optional shortened version.
abstract = "Temperature is a primary driver of the structure and function of stream ecosystems. However, the lack of stream temperature (ST) data for the vast majority of streams and rivers severely compromises our ability to describe patterns of thermal variation among streams, test hypotheses regarding the effects of temperature on macroecological patterns, and assess the effects of altered STs on ecological resources. Our goal was to develop empirical models that could: 1) quantify the effects of stream and watershed alteration (SWA) on STs, and 2) accurately and precisely predict natural (i.e., reference condition) STs in conterminous USA streams and rivers. We modeled 3 ecologically important elements of the thermal regime: mean summer, mean winter, and mean annual ST. To build reference-condition models (RCMs), we used daily mean ST data obtained from several thousand US Geological Survey temperature sites distributed across the conterminous USA and iteratively modeled ST with Random Forests to identify sites in reference condition. We first created a set of dirty models (DMs) that related STs to both natural factors (e.g., climate, watershed area, topography) and measures of SWA, i.e., reservoirs, urbanization, and agriculture. The 3 models performed well (r2  =  0.84–0.94, residual mean square error [RMSE]  =  1.2–2.0°C). For each DM, we used partial dependence plots to identify SWA thresholds below which response in ST was minimal. We then used data from only the sites with upstream SWA below these thresholds to build RCMs with only natural factors as predictors (r2  =  0.87–0.95, RMSE  =  1.1–1.9°C). Use of only reference-quality sites caused RCMs to suffer modest loss of predictor space and spatial coverage, but this loss was associated with parts of ST response curves that were flat and, therefore, not responsive to further variation in predictor space. We then compared predictions made with the RCMs to predictions made with the DMs with SWA set to 0. For most DMs, setting SWAs to 0 resulted in biased estimates of thermal reference condition."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]

# Links (optional).
url_pdf = ""
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
[[url_custom]]
name = "Journal"
url = "https://www.journals.uchicago.edu/doi/abs/10.1899/12-009.1"

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = false
  
# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
#image = ""
#caption = "My caption :smile:"

+++


