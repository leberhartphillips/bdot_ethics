# Reproducible datasets and code for:

## Evaluating the effects of tag mass on survival, breeding success, behaviour, and condition of a small, partially migratory shorebird

### *Submitted* for peer-review

#### Luke Eberhart-Hertel<sup>1</sup>, Emma M. Williams<sup>2</sup>, Ailsa McGilvary-Howard<sup>3</sup>, Ted Howard<sup>3</sup>, Tony Habraken<sup>4</sup>, Colin F. J. O’Donnell<sup>2</sup>, Clemens Küpper<sup>5</sup>, and Bart Kempenaers<sup>1</sup>

1)  *Max Planck Institute for Biological Intelligence, Department of
    Ornithology, Eberhard-Gwinner-Straße 7/8, 82319 Seewiesen, Germany*
2)  *Fauna Science Team, Department of Conservation Christchurch Office, 
    Christchurch Mail Centre, Private Bag 4715, Christchurch, 8140, New Zealand*
3)  *Kaikōura Banded Dotterel Project, Kaikōura, New Zealand*
4)  *Port Waikato Banded Dotterel Project, Port Waikato, New Zealand*
5)  *Max Planck Institute for Biological Intelligence, Behavioural
    Genetics and Evolutionary Ecology, Eberhard-Gwinner-Straße 5, 82319
    Seewiesen, Germany*

✉ For correspondence regarding the data and code in this repository and the study system, please
contact: Luke
(<a href= "mailto:luke.eberhart@bi.mpg.de">luke.eberhart[at]bi.mpg.de</a>)

In this repository you can find all the raw data and code needed to
reproduce our investigation evaluating the effects of tags on banded dotterels 
(*Anarhynchus bicinctus*) breeding in Kaikōura, New Zealand. 
Our OSF repository (https://osf.io/2rkcw/; DOI: https://doi.org/10.17605/OSF.IO/2RKCW) mirrors this GitHub repository.

For a complete overview of the methods and results presented in our manuscript, please view our project vignette: [Supplementary Material A](https://leberhartphillips.github.io/bdot_ethics/bdot_ethics.html)

![](/Users/luketheduke2/ownCloud/kemp_projects/bdot/R_projects/bdot_ethics/tabs_figs/Figure_3_complete.png)

#### Repository Contents

- [`Supplementary_Material_A.qmd`](https://github.com/leberhartphillips/bdot_ethics/blob/main/bdot_ethics.qmd)
    Quarto source code for vignette of analysis
- [`Supplementary_Material_A.html`](https://github.com/leberhartphillips/bdot_ethics/blob/main/bdot_ethics.html)
    HTML vignette of analysis for reproducibility of results. Click [`here`](https://leberhartphillips.github.io/bdot_ethics/bdot_ethics.html) for the rendered document to view in your browser.
- [`bdot_ethics.Rproj`](https://github.com/leberhartphillips/bdot_ethics/blob/main/bdot_ethics.Rproj)
    RStudio project to run and reproduce results

[**`data/`**](https://github.com/leberhartphillips/bdot_ethics/tree/main/data)

-   data for analysis of repeated measures of body condition
    [`body_traits.csv`](https://github.com/leberhartphillips/bdot_ethics/tree/main/data/body_traits.csv)
-   data for breeding fate analysis
    [`breed.csv`](https://github.com/leberhartphillips/bdot_ethics/tree/main/data/breed.csv)
-   data for multi-state apparent survival analysis
    [`ch.csv`](https://github.com/leberhartphillips/bdot_ethics/tree/main/data/ch.csv)
-   data for behavioural analysis
    [`behav.csv`](https://github.com/leberhartphillips/bdot_ethics/tree/main/data/behav.csv)
-   data for movement analysis
    [`move.csv`](https://github.com/leberhartphillips/bdot_ethics/tree/main/data/move.csv)
-   tag metadata
    [`tag_metadata.csv`](https://github.com/leberhartphillips/bdot_ethics/tree/main/data/tag_metadata.csv)

[**`out/`**](https://github.com/leberhartphillips/bdot_ethics/tree/main/out/)

-   rds file for analysis of repeated measures of body condition
    [`smi_results.Rds`](https://github.com/leberhartphillips/bdot_ethics/tree/main/out/smi_results.rds)
-   rds file for breeding fate analysis
    [`breed_results.Rds`](https://github.com/leberhartphillips/bdot_ethics/tree/main/out/breed_results.rds)
-   rds file for multi-state apparent survival analysis
    [`survival_results.Rds`](https://github.com/leberhartphillips/bdot_ethics/tree/main/out/survival_results.rds)
-   rds file for breeding fate analysis (of pairs)
    [`breed_pair_results.Rds`](https://github.com/leberhartphillips/bdot_ethics/tree/main/out/breed_results.rds)

[**`tab_figs/`**](https://github.com/leberhartphillips/bdot_ethics/tree/main/tab_figs)
folder containing the graphic in the Readme