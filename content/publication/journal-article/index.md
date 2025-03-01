
---
title: "Publications"
slug: publications
publications:
  - title: "Actin Aggregations Mark the Sites of Neurite Initiation"
    date: "2016-01-01"
    doi: "10.1007/s12264-016-0012-2"
    journal: "Neurosci Bull"
    publication_types: ["article-journal"]
  - title: "Phosphatidylinositol 3,4-bisphosphate regulates neurite initiation and dendrite morphogenesis via actin aggregation"
    date: "2017-01-01"
    doi: "10.1038/cr.2017.13"
    journal: "Cell Res"
    publication_types: ["article-journal"]
  - title: "PDGFRbeta Cells Rapidly Relay Inflammatory Signal from the Circulatory System to Neurons via Chemokine CCL2"
    date: "2018-01-01"
    doi: "10.1016/j.neuron.2018.08.030"
    journal: "Neuron"
    publication_types: ["article-journal"]
  - title: "Pericytes: The Brain's Very First Responders?"
    date: "2018-01-01"
    doi: "10.1016/j.neuron.2018.09.033"
    journal: "Neuron"
    publication_types: ["article-journal"]
  - title: "The transcription factor Hhex cooperates with the corepressor Tle3 to promote memory B cell development"
    date: "2020-01-01"
    doi: "10.1038/s41590-020-0713-6"
    journal: "Nat Immunol"
    publication_types: ["article-journal"]
  - title: "Forget IL-4 to promote memory"
    date: "2021-01-01"
    doi: "10.1038/s41590-021-01061-6"
    journal: "Nat Immunol"
    publication_types: ["article-journal"]
  - title: "Follicular dendritic cells restrict interleukin-4 availability in germinal centers and foster memory B cell generation"
    date: "2021-01-01"
    doi: "10.1016/j.immuni.2021.08.028"
    journal: "Immunity"
    publication_types: ["article-journal"]
  - title: "Chemo- and mechanosensing by dendritic cells facilitate antigen surveillance in the spleen"
    date: "2022-01-01"
    doi: "10.1111/imr.13055"
    journal: "Immunol Rev"
    publication_types: ["article-journal"]
  - title: "CD97 promotes spleen dendritic cell homeostasis through the mechanosensing of red blood cells"
    date: "2022-01-01"
    doi: "10.1126/science.abi5965"
    journal: "Science"
    publication_types: ["article-journal"]
  - title: "GPR174 signals via Galphas to control a CD86-containing gene expression program in B cells"
    date: "2022-01-01"
    doi: "10.1073/pnas.2201794119"
    journal: "Proc Natl Acad Sci U S A"
    publication_types: ["article-journal"]
  - title: "Fibroblasts: New players in the central nervous system?"
    date: "2023-01-01"
    doi: "10.1016/j.fmre.2023.01.014"
    journal: "Fundamental Research"
    publication_types: ["article-journal"]
  - title: "Dermal TRPV1 innervations engage a macrophage- and fibroblast-containing pathway to activate hair growth in mice"
    date: "2024-01-01"
    doi: "10.1016/j.devcel.2024.05.019"
    journal: "Developmental Cell"
    publication_types: ["article-journal"]
---

## Journal Articles
{{ range .Params.publications }}
### {{ .title }}
- **Date**: {{ .date }}
- **DOI**: {{ .doi }}
- **Journal**: {{ .journal }}
- **Publication Type**: {{ index .publication_types 0 }}
{{- end }}
