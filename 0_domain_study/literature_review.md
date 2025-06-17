<!-- markdownlint-disable MD013 -->

# Literature Review

Black women in the U.S. are more than three times as likely to die in childbirth than white women, and four times more likely in the UK, revealing a crisis with fatal outcomes that persist regardless of education or income level (1,2). This disparity represents a systemic issue that influences how symptoms are interpreted, how pain is assessed, and how seriously concerns are taken throughout the maternal care continuum.

A great deal of research has demonstrated that nearly half of severe maternal morbidity events and maternal deaths are preventable, making quality healthcare delivery a critical intervention point for addressing racial disparities (3). While evidence for racial bias in maternal healthcare is well-documented, current research relies predominantly on patient narratives rather than systematic analysis of clinical data and documentation patterns. This literature review examines the potential for leveraging Electronic Health Records (EHRs) and data science approaches to detect, quantify, and ultimately reduce racial bias in maternal healthcare delivery.

![temp-Image7-Wf-Jwf.avif](https://i.postimg.cc/1t91cCBj/temp-Image7-Wf-Jwf.avif)

## 🔍 Current Evidence

Race is an unscientific, socially constructed taxonomy based on an ideology that views some human population groups as inherently superior to others based on external physical characteristics or geographic origin. While the concept of race is socially meaningful, it has limited biological significance (5). According to Williams et al 1994 (5), racial and ethnic variations in health status result primarily from differences in exposure or vulnerability to behavioral, psychosocial, material, and environmental risk factors and resources.

Despite scientific evidence to the contrary, medical and epidemiological dictionaries continue to define race in terms of underlying genetic homogeneity. We focus on differences in skin color not because genes linked to pigmentation have been shown to be critical determinants of disease patterns, but because in our society, skin color serves as a central determinant of social identity and obligations, as well as a key determinant of access to desirable resources. Biological differences between racial groups have, at best, only limited explanatory power in accounting for group differences in disease outcomes. (5)

The Birthrights report (2), analyzing MBRRACE-UK's clinical records of ethnic disparities in maternal mortality cases, found no major differences in the causes of death between racial groups. However, significant disparities emerged in the quality of care received. Research on the epidemiology of racial and ethnic disparities in severe maternal morbidity (life-threatening complications during pregnancy, delivery, or postpartum) (6) consistently demonstrates that morbidity indicators are more prevalent among Black and Hispanic women compared to white women. However, these disparities reflect systemic inequities in care delivery rather than biological differences . When reviewing cases of maternal morbidity and mortality, attention must be paid to patient race, ethnicity, language, and socioeconomic status as indicators of potential exposure to systemic bias and discrimination to determine whether these social exposures played a role in adverse outcomes.

![temp-Image6-TSaj2.avif](https://i.postimg.cc/FRD5Pyns/temp-Image6-TSaj2.avif)

## 💻 Electronic Health Records Gaps and Opportunities

Health IT can standardize care through protocols, checklists, and clinical decision support systems integrated into EHRs. These tools can reduce disparities by improving adherence to clinical guidelines and reducing biased decision-making (7).

More importantly, EHRs offer unprecedented opportunities to detect bias through computational analysis of clinical documentation. However, Jean-François et al (7). identified a clear gap in assessing racial disparity risks through health IT tools. Recent research analyzing 1.8 million critical care records (8) successfully identified patterns of gender and ethnicity bias in clinical language using Natural Language Processing (NLP). This methodology could determine whether racism against pregnant Black women can be detected through clinical notes and medical documentation.

A systematic review demonstrates that stigmatizing language in clinical documentation—words implying judgment, disbelief, or negative assumptions—perpetuates disparities, especially for racially minoritized populations (9). Natural Language Processing was used in four studies within that review to automatically extract stigmatizing terms, providing evidence that EHRs may reflect biased language, under-documentation of symptoms, or systematic downplaying of Black patients' concerns.

If Black pregnant women's symptoms or pain are less frequently or less seriously recorded compared to white women, this exposes a **documentation gap** that leads to substandard care. Such findings provide concrete evidence of how implicit bias translates into measurable differences in clinical documentation and adverse outcomes.

The convergence of computational capabilities with growing awareness of healthcare disparities presents a critical opportunity to move beyond identifying disparities to understanding their mechanisms. While previous research has documented the existence of racial disparities in maternal outcomes, the pathways through which bias manifests in clinical interactions—from initial documentation patterns to pain assessment protocols to care escalation decisions—remain insufficiently explored. EHR analysis offers the potential to shed light on these hidden processes by examining not just what care was provided, but how clinical decisions were documented, communicated, and acted upon across racial lines. Understanding these interaction patterns and their relationship to maternal outcomes represents an essential step toward developing targeted interventions that address bias at its source rather than merely its consequences.

![temp-Image-GRW55t.avif](https://i.postimg.cc/Dz6MF2Qx/temp-Image-GRW55t.avif)

## 📚 Referances

1. Fleszar, L. (2023, August 18). _Maternal death rates more than doubled for every racial and ethnic group: Black women hit hardest_. _Fortune_. [https://fortune.com/well/article/black-women-maternal-mortality-rate-increase/](https://fortune.com/well/article/black-women-maternal-mortality-rate-increase/)
2. Birthrights. (2022). _Systemic racism, not broken bodies: An inquiry into racial injustice and human rights in UK maternity care_.  [https://birthrights.org.uk/wp-content/uploads/2022/05/Birthrights-inquiry-systemic-racism-May-22-web-1.pdf](https://birthrights.org.uk/wp-content/uploads/2022/05/Birthrights-inquiry-systemic-racism-May-22-web-1.pdf)
3. Howell, E. A. (2018). _Reducing disparities in severe maternal morbidity and mortality_. _Clinical Obstetrics and Gynecology, 61_(2), 387–399. [https://doi.org/10.1097/GRF.0000000000000349](https://doi.org/10.1097/GRF.0000000000000349)
4. Jean‑Francois, B., Lash, T. B., Dagher, R. K., Green Parker, M. C., Han, S. B., & Johnson, T. L. (2021). _The potential for health information technology tools to reduce racial disparities in maternal morbidity and mortality_. _Journal of Women’s Health, 30_(2), 274–279. [https://doi.org/10.1089/jwh.2020.8889](https://doi.org/10.1089/jwh.2020.8889)
5. Williams, D. R., Lavizzo‑Mourey, R., & Warren, R. C. (1994). _The concept of race and health status in America._ _Public Health Reports, 109_(1), 26–41.  [https://pmc.ncbi.nlm.nih.gov/articles/PMC1402239/](https://pmc.ncbi.nlm.nih.gov/articles/PMC1402239/)
6. Howell, E. A., & Zeitlin, J. (2018). _Improving hospital quality to reduce disparities in severe maternal morbidity and mortality._ _Seminars in Perinatology, 41_(5), 266–272. [https://doi.org/10.1053/j.semperi.2017.07.012](https://doi.org/10.1053/j.semperi.2017.07.012)
7. Jean‑Francois, B., Bailey Lash, T., Dagher, R. K., Parker, M. C., Han, S. B., & Lewis Johnson, T. (2020, November 20). _The potential for health information technology tools to reduce racial disparities in maternal morbidity and mortality_. _Journal of Women’s Health, 30_(2), 274–279. [https://doi.org/10.1089/jwh.2020.8889](https://doi.org/10.1089/jwh.2020.8889)
8. Taira, T. (2022). _Gender and Ethnicity Bias in Medicine: A Text Analysis of 1.8 Million Critical Care Records_.  [https://doi.org/10.31234/osf.io/xpb2k](https://doi.org/10.31234/osf.io/xpb2k)
9. Barcelona, V., Scharp, D., Idnay, B. R., Moen, H., Cato, K., & Topaz, M. (2024). _Identifying stigmatizing language in clinical documentation: A scoping review of emerging literature_. _PLOS ONE_. Advance online publication. [https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0303653](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0303653)

  <!-- markdownlint-enable MD013 -->