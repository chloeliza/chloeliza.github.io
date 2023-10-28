---
layout: post
title:  "Data science and a paradigm shift for psychiatry"
date: 2021-02-03
excerpt: "Essay in ''Analytics Interpreted: A Compilation of Perspectives.''"
image: /img/dataanalytics.jpg
hero_image: /img/dataanalytics.jpg
hero_height: is-small
hero_darken: true
categories: [neuroscience, mental-health]
---

-----

This essay was originally published in [_Analytics Interpreted: A Compilation of Perspectives_](https://www.amazon.com/gp/product/B08VZXD469?pf_rd_r=RGNEH7A8V5H677Q5J9D9&pf_rd_p=5ae2c7f8-e0c6-4f35-9071-dc3240e894a8&pd_rd_r=c728740f-c568-4668-8075-81b382152e63&pd_rd_w=dMB0l&pd_rd_wg=Zl6N3&ref_=pd_gw_unk) by Women in Analytics, eds. Rehgan Avon and Dave Cherry. (2021)

**Data science and a paradigm shift for psychiatry**

The mental health field is moving towards a paradigm shift in our understanding of psychiatric illness. Neuroscience is advancing knowledge about the inner workings of the brain and changes in genes, cells, and circuits that contribute to mental illness, while psychology continues to refine behavioral and sociological perspectives on pathology. Data science is needed to integrate these approaches and build the models that will shift away from discrete diagnostic categories based solely on behavioral symptoms and towards a multi-dimensional understanding of mental health and disease.

Historically, as well as in the present day, the DSM (Diagnostic and Statistical Manual) of Mental Disorders has guided the classification and diagnosis of conditions such as depression, anxiety, and schizophrenia. Now in its fifth edition, the DSM approaches mental disorders as categories and subcategories defined by behavioral symptoms. For example, major depressive disorder (MDD) is a diagnostic category that resides under the “depressive disorders” classification. To meet the criteria for a diagnosis of MDD, one must exhibit five or more behavioral symptoms (such as anhedonia, low mood, suicidal thoughts or behavior, or sleeping more/less) out of a list of eight descriptive possibilities during the same two-week period. 

**Thinking beyond the box**

Psychiatry has relied on this “box” model of mental disorders since 1952, when the first edition of the DSM was published. However, advances in neuroscience – as well as the realities of the lived experience of mental illness – have exposed many of the limitations of placing behavioral symptoms into discrete diagnostic boxes. Many disorders are co-morbid with each other, such as depression and anxiety or depression and autism, relationships that are not readily clear according to the DSM categories. Perhaps most importantly, the DSM “box” model focuses solely on behavioral manifestations of a disorder for diagnoses, to the exclusion of other predictors ranging from the genetic to the sociological.

With these limitations in mind, the National Institute of Mental Health (NIMH) launched in 2010 an initiative called the Research Domain Criteria (RDoC) project. RDoC is an ambitious yet necessary effort to integrate neurobiological, behavioral, and demographic features of mental health into comprehensive models of pathology. Instead of categorizing illnesses into diagnostic boxes, RDoC aspires to a “domain” model of mental illnesses where conditions are understood as dysfunctions across domains of brain systems and behavior. RDoC is continuously evolving, and at the time of this writing includes six domains:

1. Negative valence systems
2. Positive valence systems
3. Cognition
4. Social processing
5. Arousal/regulatory systems
6. Sensorimotor systems

The depression symptom of anhedonia, for instance, may be understood as disruptions in positive valence systems with biological dysfunction (impaired dopamine transmission, dysfunctional reward pathways in the brain) and behavioral manifestations.

Advantages of the RDoC approach include the ability to build an understanding of the relationship between different disorders (e.g., the similarities between depression and anxiety) and integrate biological and behavioral information. At present, an RDoC-based understanding of mental illness has not been employed for diagnosis and treatment, but scientists and clinicians are collaborating to build these multi-dimensional models of neuropsychiatric conditions.

**How data science can help**

Within this model-building endeavor, there is a much-needed role for data scientists to play in integrating RDoC domains (negative valence, etc.) and levels of analysis (genetics, behavior, etc.). An example analytic approach with great potential for psychiatry is unbiased clustering. In genetics, unbiased clustering can be used to group similar cells together based on their gene expression profiles. In psychiatry, unbiased clustering could be similarly applied to group patients together based on their symptom profiles, including biological and behavioral symptoms.

Using this approach, one can envision t-distributed stochastic neighbor embedding (t-SNE) plots where spatially arranged clusters of patients represent the relationships between patterns of symptoms. Such a t-SNE plot might even be able to parse heterogeneity in a disorder like depression by identifying clusters of patients, closely related in space on the plot, who have a strong genetic component to their symptoms vs. those whose condition is more attributable to stress or trauma. Further heterogeneity could also be revealed, such as similarities between depression patients who sleep more compared to those who sleep less. Patients with anxiety symptoms would likely cluster near or within depression-related clusters, highlighting the close relationship between these two conditions. Unbiased clustering and dimensionality reduction analyses built from scientific and clinical data has the potential to transform the way we delineate boundaries between mental health conditions, which may also revolutionize treatment approaches and pave the way for personalized, precision psychiatry. 

Neuropsychiatric disorders may also be able to be modeled in silico using advanced data analytic and simulation techniques. Disorders such as depression, autism, and schizophrenia are increasingly being thought of as network disorders that must be comprehended as complex interactions between various regions of the brain and the connections and activity of neurons within those brain regions. For example, depression may be a network disorder with disrupted activity and connectivity between regions like the prefrontal cortex (cognitive processing and emotional regulation), the amygdala (positive and negative valence assignments) and the basal ganglia (reward processing), among others. Computational approaches can simulate these networks and mathematically alter parameters such as the number and strength of connections between neurons, the number of neurons within a network, and the activity of these neurons.

_The Rewiring Brain: A Computational Approach to Structural Plasticity in the Adult Brain_, edited by Arjen van Ooyen and Markus Butz-Ostendorf (Elsevier), contains numerous examples of such mathematical models for simulating network plasticity and activity with implications for understanding stroke or brain lesion pathology and recovery. However, similar mathematical models have sparsely been applied to neuropsychiatric disorders. Simulations of network function and dysfunction could also transform our understanding of how mental pathology transpires in the brain. 

As science moves more towards open data sharing, there are growing information repositories that can be utilized. There is also a need for data scientists to streamline the organization of and access to these data. For example, the NIMH Data Archive (NDA) hosts datasets from RDoC-inspired studies that include imaging, clinical, and omics (genomics, transcriptomics, proteomics) data. These open source datasets, together with ongoing scientific and clinical research studies, provide the foundations for building models of neuropsychiatric conditions.

The mental health field has long struggled with incomplete understandings of pathology, arbitrary diagnostic delineations, and trial-and-error approaches to treatment, and a scientifically informed paradigm shift in mental illness diagnosis and treatment could improve outcomes for millions of patients. Data science is vital in this endeavor to integrate biological and behavioral variables across domains of brain systems and behavior. 


-----