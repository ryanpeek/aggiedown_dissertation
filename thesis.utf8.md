---
# UW thesis fields
title: "Population genetics of a sentinel stream-breeding frog (*Rana boylii*)"
author: "Ryan A Peek"
year: "2018"
month: "December"
program: "Ecology"
uccampus: "Davis"
report: "DISSERTATION"
degree: "DOCTOR OF PHILOSOPHY"
prevdegreeA: "B.S. (University of California, Davis) 2002"
prevdegreeB: "M.S. (University of San Francisco) 2010"
chair: "Michael R. Miller"
signature1: "Peter B. Moyle"
signature2: "Mark W. Schwartz"
abstract: "*Rana boylii* is an imperiled frog species native to CA and OR, and it is currently designated as a species of special concern in the state of CA. It has been petitioned as candidate for federal (USFWS) and state (CDFW) listing. As a lotic breeding amphibian, *R. boylii* is tied closely to local flow regimes in the watersheds it inhabits and is therefore particularly sensitive to alterations to the natural flow regime. Effective conservation management of this species should consider and prioritize maintenance of genetic diversity as part of any listing decision because it is closely related to the evolutionary capacity for adaptation to environmental change. Conservation of genetic diversity in this species will require several components, including refining potential conservation units (i.e., distinct population segments) and quantifying of genetic diversity and genetic diversity trajectories across the species range. To assess these components, fine-scale and landscape-scale analyses were conducted using genomic data from over 600 samples from 89 localities across the range of the species. Six genomically-distinct groups were identified, as well as population subdivisions at local watershed scales. One major impact on *R. boylii* populations has been river regulation. River regulation has been implicated as a cause of fundamental changes to downstream aquatic ecosystems. Regulation changes the natural flow regime which may restrict population connectivity and decrease genetic diversity in some species. Since population connectivity and the maintenance of genetic diversity are fundamental drivers of long-term persistence, understanding the extent that river regulation impacts these critical attributes of genetic health is an important goal. However, the extent to which *R. boylii* populations in regulated rivers have maintained connectivity and genetic diversity is unknown. The impacts of river regulation on *R. boylii* were investigated with genomic data to explore the potential for long-term persistence of *R. boylii* under continued regulation. *R. boylii* in regulated rivers showed striking patterns of isolation and trajectories of genetic diversity loss relative to unregulated rivers. For example, river regulation explained the greatest amount of variance in population genetic differentiation compared with other covariates including geographic distance. Importantly, patterns of connectivity and genetic diversity loss were observed regardless of regulation level but were most prominent in locations with the greatest regulation intensity. Using the same genomic data, fine-scale analyses of *R. boylii* and *R. sierrae* in a single region of the Sierra Nevada of California was conducted to evaluate the potential for hybridization between species. Hybridization between species may combine parental genotypes in ways that yield reproductively sterile or isolated lineages, and hybridization events may be short-lived and difficult to detect. Limited hybridization between the species was detected in the Feather basin, though it appears these are terminal events based on PCA, admixture, and tests of heterozygosity using species diagnostic SNPs. Finally, rangewide quantification and comparison of genomic variation across populations indicates the southern coast, southern Sierra Nevada, and Northern Sierra/Feather basin in California should have high prioritization in conservation efforts due to low genomic diversity and trajectories of diversity loss. More broadly, these results demonstrate both the critical need for regional conservation in a sentinel river species, and the utility and power of genetic methods for assessing and monitoring sensitive species across many scales."
acknowledgments: "For all the curious people who have come before and hopefully after, I want to acknowledge you, and I hope we can do better to inspire and support those voices that may not have had the opportunities or priviledge I have had. I am lucky to have had all I have had, and finishing a dissertation requires a community, and this dissertation would not have happened if it wasn’t for the amazing community of family, friends, and colleagues who helped me every step of the way. In particular, thank you to my partner, wife and best-friend Leslie—you are my sun and gravity—you held me together, anchored our family, and made it possible to run this crazy academic ultra-marathon. To my dearest little tadpoles, Connor and Genevieve, you inspire me, you make me laugh every day, and you remind me the world still has hope as long as we nourish joy and curiosity. Thank you for being you, and I hope one day you forgive me for the amount of time I’ve spent staring at a computer. Thanks to my mom for all the support, love, and baked goods. Sibling, thank you for consistently inspiring me, listening to me, and being the best sibling one could ask for. And for all my close friends, bandmates, and officemates (you know who you are), you keep me sane, you motivate me, and you remind me every day that I really love this crazy journey. John, your shed and couch have probably single-handedly kept me anchored in ways I can't even express...also your friendship. Thank you for your time, humor, and general levity. Thanks to my Dad, who has cajoled, pestered, and annoyed me for far too long to “get a PhD”, thanks for believing it was possible even when I didn’t. Also, please never suggest anything like this again. And to my committee and my colleagues at the Center for Watershed Sciences, you have all been an amazing resource in providing feedback, guidance, and support throughout my graduate student career. Finally, to my cohort and fellow students in the GGE, this has been a great place to grow and mature as a scientist and researcher. Thank you all."
dedication: |
  "*The good life of any river may depend on the perception of its music; and the preservation of some music to perceive.*"    
  (Aldo Leopold)    
      
  > "*One thing to remember is to talk to the animals. If you do, they will talk back to you. But if you don’t talk to them, they won’t talk back to you, then you won’t understand. And when you don’t understand, you will fear, and when you fear, you will destroy the animals, and if you destroy the animals, you will destroy yourself*"    
  (Chief Dan George, Tseil-Waututh Nation, North Vancouver)
# End of UCD thesis fields
knit: "bookdown::render_book"
site: bookdown::bookdown_site
output: 
  gauchodown::thesis_pdf: 
    latex_engine: xelatex
#  gauchodown::thesis_gitbook: default
#  gauchodown::thesis_word: default
#  gauchodown::thesis_epub: default
bibliography: bib/peek_dissertation.bib
# Download your specific bibliography database file and refer to it in the line above.
csl: csl/ecology.csl
# Download your specific csl file and refer to it in the line above.
link-citations: yes
lot: true
lof: true
linkcolor: blue
citecolor: blue
urlcolor: blue
#space_between_paragraphs: true
# Delete the # at the beginning of the previous line if you'd like
# to have a blank new line between each paragraph
#header-includes:
#- \usepackage{tikz}
---

# UW thesis fields

Placeholder



<!--chapter:end:index.Rmd-->




# Flow regulation associated with decreased genetic health of a river-breeding frog species {#reg-health}

\chaptermark {Flow Regulation}

## Introduction

Rivers simultaneously connect and carve the landscapes through which they flow. Rivers provide corridors of connectivity for riparian and aquatic organisms such as fish, amphibians, and macroinvertebrates [@pringle_what_2003; @wiens_riverine_2002], while also acting as physical barriers on the landscape for many terrestrial organisms [@caze_could_2016; @voelker_river_2013]. Hydrologic connectivity [@pringle_what_2003] transfers energy, organisms and ultimately genetic variation and thus is a critical component for population persistence in dynamic systems where populations must constantly adapt to temporal and spatial changes. In Mediterranean climates, rivers have strong seasonal patterns associated with cold, wet winters and warm, dry summers. Native aquatic organisms have evolved life histories well adapted to these natural patterns, which are both predictable and seasonal [@tonkin_seasonality_2017; @yarnell_ecology_2010]. 

River regulation, or the hydrological alteration of flow by dams and diversions, impacts the seasonal and interannual flow variability within a watershed. Regulation changes the natural flow regime and dramatically alters geomorphic and hydrologic connectivity of watersheds [@poff_homogenization_2007], which may restrict natural population connectivity [@schick_directed_2007; @shaw_importance_2016]. River regulation can change flow frequency, magnitude, duration, timing, and rate of change, which can have significant impacts on aquatic organisms and ecological processes [@poff_homogenization_2007; @yarnell_ecology_2010]. River regulation, and more specifically, regulation associated with hydropower generation, has been implicated as a cause of fundamental changes to downstream aquatic ecosystems [@bunn_basic_2002; @moyle_rapid_2011; @power_dams_1996]. The hydrological regimes of over half of the world’s largest rivers have been altered by large dams [@nilsson_fragmentation_2005] and only recently has the extent of flow alteration and the associated ecosystem-level impacts been acknowledged [@dudgeon_freshwater_2006; @murchie_fish_2008; @pringle_hydrologic_2001]. 

Changes to abiotic processes caused by river regulation can have a substantial impact on biotic communities. The negative effects of river regulation on migration and loss of spawning habitat [@fuller_linking_2011; @kupferberg_effects_2012; @lind_effects_1996; @rolls_environmental_2017], reductions in population abundances and diversity [@fuller_linking_2011; @guzy_influence_2018; @sabo_designing_2017; @scribner_applications_2016; @vorosmarty_global_2010; @werth_dams_2014; @zhong_environmental_1996], and fragmentation [@guzy_influence_2018; @sabo_designing_2017; @scribner_applications_2016; @vorosmarty_global_2010; @werth_dams_2014] have been well documented. However, most rivers have not been regulated for long periods (e.g., less than 100 years) compared to the time these organisms had to adapt to pre-anthropogenic river flow. In regulated rivers that organisms still occupy, it remains unknown whether populations can persist long-term with continued regulation. In other words, while some species may have persisted since regulation began in a system (e.g., several decades), this does not necessarily mean these populations will persist into the future under current flow regulation regimes. Thus, exploring the potential for long-term persistence of populations under different flow regimes is a crucial component for guiding conservation efforts yet remains a significant gap. 

One tool that can help address this gap is the integration of genetics and hydrology to better assess the impact of river regulation on aquatic organisms [@scribner_applications_2016]. Although aquatic organisms are often difficult to count and monitor by conventional methods, genetic monitoring can be a powerful tool to assess population health by revealing factors such as fragmentation and population declines. It is widely recognized that reductions in population connectivity can increase isolation and inbreeding, leading to a potential "extinction vortex" [@gilpin_minimum_1986], yet there is limited understanding of how flow alteration may impair the processes crucial for maintenance of genetic variation and thus adaptive capacity. In addition, there is a current pressing need for more effective and flexible watershed management tools, particularly in relation to monitoring aquatic populations and implementation of environmental flows [@grantham_climatic_2010]. Thus, population genetics could be a powerful tool to understand the influence of different flow regimes on population health and this information could facilitate improved flow management to better protect aquatic populations. 

The river-breeding foothill yellow-legged frog (*Rana boylii*; FYLF) historically occurred in lower and mid-elevation streams and rivers from Southern Oregon to northern Baja California west of the Sierra-Cascade crest [@stebbins_field_2003]. *Rana boylii* are intimately linked with river hydrology because they have evolved to spawn in synchrony with natural flow cues associated with seasonal spring snowmelt or rain recession periods [@bondi_transferability_2013; @kupferberg_hydrologic_1996; @yarnell_ecology_2010; @yarnell_management_2016]. However, population declines have been documented across the former range of this species, particularly in southern California and the Sierra Nevada where it has been extirpated from approximately 50 percent of its historical range [@davidson_spatial_2002; @jennings_amphibian_1994]. \par

In California, particularly in the Sierra Nevada, river regulation may be a significant environmental stressor [@kupferberg_effects_2012; @lind_effects_1996]. Regulated river reaches typically alter flows by augmenting or diverting winter and spring runoff, thereby reducing or eliminating flow cues and disrupting natural flow regimes. Aseasonal flow fluctuation from river regulation can scour (detach from substrate) or desiccate *R. boylii* egg masses, and the loss of clutches may have a significant demographic impact because only one egg mass is laid per year. In many regulated rivers in the Sierra Nevada, *R. boylii* populations are now restricted to small unregulated tributaries flowing into the regulated mainstem. \par

Here, we investigated the impacts of river regulation on genetic diversity of *R. boylii* populations across three different flow regimes. Given that population connectivity and genetic diversity are known to be play critical roles in long-term species persistence, we explored the association between these metrics and levels of river regulation. Our goal was to assess the genetic health (through metrics of genetic diversity) of *R. boylii* under different river regulation regimes to better inform the potential for long-term persistence. These data can be used to prioritize management and conservation efforts for *R. boylii*, as well as demonstrate the potential utility of genetics for future conservation monitoring efforts in aquatic species.

## Methods

### Sample collection and DNA extraction {#ch1samplecollection}

345 *R. boylii* buccal or tissue samples were used in this study across six different rivers (Table \@ref(tab:CH1T1), [Appendix, S1](#supptables)). Field sampling was conducted following @heyer_measuring_1994, under CDFW SCP Permit #0006881, with IACUC protocol #19327. Individual post-metamorphic frogs were buccal-swabbed following established protocols [@broquet_buccal_2007; @goldberg_frogs_2003; @pidancier_buccal_2003]. Each post-metamorphic individual was comprehensively swabbed underneath tongue and cheek for approximately one minute. Swabs were air dried for approximately five minutes and placed in 1.5 mL microcentrifuge tubes while in the field. Samples were stored in the laboratory at -80°C until DNA extraction. Where possible, tail clips from tadpole larvae were collected, and tadpoles greater than 15 mm total length were targeted [@parris_assessing_2010; @wilbur_ecological_1990]. One small (<3mm) tail clip was taken per individual tadpole and dried on Whatman qualitative filter paper (grade 1) and stored at room temperature. Some older tissue samples consisted of toe clips placed in 100% ethanol for storage, and DNA extraction from these samples used Qiagen DNeasy kits following the manufacturer’s protocol. Buccal swabs and tail clip DNA were extracted with a magnetic bead–based protocol [@ali_rad_2016] and quantified using Quant-iT PicoGreen dsDNA Reagent (Thermo Fisher Scientific) with an FLx800 Fluorescence Reader (BioTek Instruments).  



\begin{landscape}\begin{table}

\caption{(\#tab:CH1T1)Sampling and locality information for population genomic analysis in the Yuba, Bear, and American watersheds in the northern Sierra Nevada of California, USA. The number of individuals (n) is given for the total number sequenced per location and the number of individuals that were retained after filtering across the 8,533 baits. NHD refers to the National Hydrography Dataset by USGS (U.S. Geological Survey, National Hydrography Dataset, Digital data, accessed, August 2017).}
\centering
\resizebox{\linewidth}{!}{
\begin{tabular}[t]{lrllllrrrrrrr}
\toprule
Site Name & SiteID & Locality & River & Watershed & Regulation Type & Lat. & Lon. & Elev. (m) & NHD Stream Order & NHD Total Drainage Area (sq. km) & n initial & n retained\\
\midrule
BEAR & 20 & Chicago Powerhouse & Bear & Bear & Bypass & 39.17484 & -120.8998 & 665.7990 & 4 & 136.0 & 6 & 6\\
BEAR\_GRHN & 16 & Greenhorn Creek & Bear & Bear & Bypass & 39.23206 & -120.9019 & 820.5347 & 2 & 11.0 & 15 & 6\\
BEAR\_STH2 & 19 & Steep Hollow Creek US & Bear & Bear & Bypass & 39.19444 & -120.8878 & 704.6578 & 2 & 45.0 & 7 & 6\\
BEAR\_STHA & 18 & Hawkins Ravine & Bear & Bear & Bypass & 39.18833 & -120.8981 & 706.9961 & 2 & 4.0 & 3 & 3\\
BEAR\_STHC & 17 & Steep Hollow Creek DS & Bear & Bear & Bypass & 39.20231 & -120.8754 & 736.8513 & 2 & 52.0 & 13 & 12\\
\addlinespace
MFA\_AMEC & 1 & American Canyon & MF American & American & Hydropeaking & 38.93396 & -120.9436 & 240.3928 & 2 & 9.0 & 16 & 6\\
MFA\_GASC & 2 & Gas Canyon & MF American & American & Hydropeaking & 38.96651 & -120.9325 & 241.8506 & 1 & 13.0 & 6 & 6\\
MFA\_TODC & 3 & Todd Creek & MF American & American & Hydropeaking & 38.96385 & -120.9216 & 367.7263 & 2 & 10.0 & 11 & 9\\
MFY\_OREGCK & 27 & Oregon Creek & Middle Yuba & Yuba & Bypass & 39.44188 & -121.0575 & 620.4250 & 4 & 375.0 & 15 & 13\\
MFY\_US\_OH & 28 & US Our House Dam & Middle Yuba & Yuba & Bypass & 39.41305 & -120.9903 & 624.1467 & 4 & 375.0 & 13 & 12\\
\addlinespace
NFA & 13 & Iowa Hill Mainstem & NF American & American & Unregulated & 39.11115 & -120.9168 & 386.4710 & 4 & 605.0 & 36 & 30\\
NFA\_BUNC & 8 & Bunch Canyon & NF American & American & Unregulated & 39.03762 & -120.9103 & 286.2874 & 3 & 27.0 & 15 & 14\\
NFA\_EUCH & 14 & Euchre Bar & NF American & American & Unregulated & 39.18492 & -120.7620 & 579.5186 & 4 & 508.0 & 13 & 11\\
NFA\_INDC & 10 & Indian Creek & NF American & American & Unregulated & 39.05665 & -120.9085 & 296.1071 & 2 & 24.0 & 12 & 11\\
NFA\_POND & 7 & Ponderosa Bridge & NF American & American & Unregulated & 38.99995 & -120.9406 & 240.8255 & 5 & 857.0 & 5 & 5\\
\addlinespace
NFA\_ROBR & 12 & Robbers Ravine & NF American & American & Unregulated & 39.10451 & -120.9267 & 400.0005 & 1 & 4.0 & 30 & 11\\
NFA\_SAIC & 15 & Sailor Canyon & NF American & American & Unregulated & 39.21694 & -120.4960 & 1005.5781 & 3 & 166.0 & 8 & 5\\
NFA\_SHIC & 9 & Shirttail Creek & NF American & American & Unregulated & 39.04446 & -120.8994 & 525.7589 & 4 & 141.0 & 16 & 15\\
NFA\_SLAR & 11 & Slaughter Ravine & NF American & American & Unregulated & 39.09865 & -120.9255 & 356.0791 & 2 & 6.0 & 8 & 8\\
NFMFA\_SC & 4 & NFMFA-Skunk Canyon & MF American & American & Hydropeaking & 39.02237 & -120.7369 & 521.5720 & 2 & 6.0 & 18 & 18\\
\addlinespace
NFY & 29 & Rocky Rest Mainstem & North Yuba & Yuba & Unregulated & 39.51190 & -120.9774 & 704.6863 & 5 & 669.0 & 15 & 12\\
NFY\_SLATE\_CGRAV & 30 & Slate Creek & North Yuba & Yuba & Bypass & 39.68913 & -120.9389 & 1330.9373 & 3 & 58.7 & 4 & 4\\
RUB\_LCUS & 6 & Rubicon-Long Canyon & MF American & American & Bypass & 38.98887 & -120.6900 & 415.1026 & 5 & 806.0 & 9 & 8\\
RUB\_USPH & 5 & Rubicon-US Powerhouse & MF American & American & Bypass & 38.99928 & -120.7233 & 360.5759 & 5 & 816.0 & 11 & 11\\
SFY & 26 & US Canyon Creek & South Yuba & Yuba & Bypass & 39.35386 & -120.7342 & 889.7745 & 4 & 365.0 & 6 & 6\\
\addlinespace
SFY\_LOGA & 25 & Logan Creek & South Yuba & Yuba & Bypass & 39.36914 & -120.8526 & 1201.1790 & 1 & 5.0 & 5 & 4\\
SFY\_MISC & 24 & Missouri Canyon & South Yuba & Yuba & Bypass & 39.36096 & -120.8814 & 1094.6312 & 2 & 5.0 & 8 & 6\\
SFY\_ROCKCK & 23 & Rock Creek & South Yuba & Yuba & Bypass & 39.32983 & -120.9863 & 593.5214 & 4 & 710.0 & 3 & 3\\
SFY\_SHADYCK & 21 & Shady Creek & South Yuba & Yuba & Bypass & 39.35433 & -121.0590 & 675.0255 & 2 & 15.0 & 14 & 12\\
SFY\_SPRINGCK & 22 & Spring Creek & South Yuba & Yuba & Bypass & 39.33233 & -120.9890 & 595.1054 & 3 & 24.0 & 4 & 4\\
\bottomrule
\end{tabular}}
\end{table}
\end{landscape}

### Sequencing and de novo assembly {#denovo}

To produce a high-quality genomic resource for a frog species with a large genome size, we first interrogated a large fraction of the genome using a SbfI restriction enzyme and high-density RAD sequencing on an Illumina HiSeq [@baird_rapid_2008; @miller_rapid_2007]. Paired-end sequence data were generated from 24 *R. boylii* individuals collected previously [@peek_landscape_2010] from coastal and Sierra Nevada populations in California, USA [(Appendix, S2)](#supptables).  RAD libraries were constructed following the protocol described in @ali_rad_2016. *De novo* loci discovery and contig extension were carried via custom PERL scripts [@miller_conserved_2012] using the alignment program Novoalign and the genome assembler PRICE [@ruby_price_2013]. This pipeline resulted in a set of 77,544 RAD contigs ranging from 300 to 800 bp which served as a *de novo* partial genome reference for all subsequent downstream analyses [(Appendix, S3)](#supptables). Using these data, we filtered data to loci with 4 or fewer SNPs, and randomly selected 10,000 loci from this subset. Using these RADSeq data, 8,533 RAD capture baits (120bp) were designed by Arbor Biosciences from the de novo alignment [(Appendix, S4)](#supptables).

### Rapture sequencing {#rapture}

We then performed Rapture on all study samples to identify putative high-quality SNPs [(Appendix, S1)](#supptables) using RAD capture baits. Three different sequencing runs on an Illumina HiSeq were merged together, filtered, and duplicates were removed using ANGSD and Samtools [@li_sequence_2009]. Sampled individuals were aligned against the de novo partial genome reference using the BWA-MEM algorithm [@li_fast_2010; @li_aligning_2013] and saved to BAM format. SAMtools was used to sort, filter for proper pairs, remove PCR duplicates, and index binary alignment map (BAM), as well as merge sequences from multiple libraries [@li_sequence_2009].

### Principal component analysis

A probabilistic framework was used to discover SNPs for PCA as it does not require calling genotypes and is suitable for low-coverage sequencing data [@fumagalli_quantifying_2013; @korneliussen_calculation_2013]. All Rapture analyses were conducted using Analysis of Next Generation Sequencing Data (ANGSD) [@korneliussen_angsd_2014]. ANGSD analyses were conducted following methods from @prince_evolutionary_2017, with a minimum mapping quality score (`minMapQ`) of 10, a minimum base quality score (`minQ`) of 20, and the genotype likelihood model (`GL 1`) [@li_statistical_2011]. To maximize data quality, samples with less than 100,000 aligned reads were excluded [(Appendix, S1)](#supptables) and only sites represented in at least 50% of the included samples (`minInd`) were used. Settings used in ANGSD for PCA to identify polymorphic sites included a `SNP_pval` of 1e^-6^, inferring major and minor alleles (`doMajorMinor 1`), estimating allele frequencies (`doMaf 2`) [@kim_estimation_2011], retaining SNPs with a minor allele frequency of at least 0.05 `(minMaf`), genotype posterior probabilities calculated with a uniform prior (`doPost 2`), and the `doIBS 1` and `doCov 1` options were used to generate PCA data. Principal components (PC) summarizing population structure were derived from classic eigenvalue decomposition and were visualized using the ggplot2 package in R [@r_core_team_r_2017].

### Genetic differentiation and diversity estimates

Mean scaled F~ST~ was used to quantify genetic differentiation between populations [@rousset_genetic_1997; @wright_isolation_1943]. Genome-wide F~ST~ between population pairs was estimated by first calculating a site frequency spectrum (SFS) for each population (`doSaf`) [@nielsen_snp_2012] with ANGSD. The two-dimensional SFS and global F~ST~ between each population pair were then estimated using realSFS [@korneliussen_angsd_2014]. F~ST~ was calculated between each pair of collection locations within a watershed, and the mean of all pairwise calculations within that watershed was calculated for each location. We calculated the river distances (distance along river network) between locations within watersheds using the riverdist package in R [@tyers_riverdist_2017], and used the mean pairwise river distance (km) to all other locations within the watershed. These values were plotted and a generalized linear model was fitted ($F_{ST}$ ~ $Mean River Distance$) in R [@r_core_team_r_2017]. To calculate Watterson’s $\theta$ ($\theta_S$) [@watterson_number_1975], and Tajima’s $\theta$ ($\theta_\pi$) [@tajima_evolutionary_1983], we used SFS that were estimated as described above as priors (`pest`) to calculate each statistic for each site (`doThetas`), and then averaged to obtain a single value for each statistic [@korneliussen_calculation_2013]. 

### Boosted regression tree modeling of variance in F~ST~

We used boosted regression tree (BRT) models with the R packages gbm [@ridgeway_gbm_2015] and dismo [@hijmans_dismo_2017] to assess the relative influence of river regulation as compared to other covariates. Boosted regression trees (BRT) are suitable frameworks for large and complex ecological datasets because they do not assume normality, nor linear relationships between predictor and response variables and they ignore non-informative predictor variables [@graham_influence_2008; @steel_associating_2017]. BRTs use iterative boosting algorithms to combine simple decision trees to improve model performance [@death_boosted_2007] and provide a robust alternative to many traditional statistical methods [@guisan_what_2007; @phillips_maximum_2006]. BRTs assess the relative impact of modeled variables by calculating the number of times a variable is selected for splitting a tree across all folds of the cross validation. Following @steel_associating_2017, estimates of relative influence for each predictor variable were used to evaluate the relative contribution a variable had in predicting the response. To evaluate the relative influence of covariates on F~ST~, models were trained using river distance (km), elevation (m), upstream drainage area (km2), Strahler stream order, and number of samples per location. Stream segment data on elevation, length, slope, stream order, and drainage area were derived from NHD Plus attributes (U.S. Geological Survey, National Hydrography Dataset, Digital data, accessed, August 2017 at http://nhd.usgs.gov/data.html). In addition, $\Delta \theta$ $(\theta_\pi - \theta_S)$ was included to assess the effect of genomic variation on F~ST~ across regulation types.

Model training and fitting were conducted following methods previously described in @steel_associating_2017. To reduce overfitting, the learning rate (also known as the shrinking rate) was set to 0.001. Stochastic gradient boosting was utilized to reduce prediction error [@death_boosted_2007] and the fraction of training data sampled to build each tree was 0.75, within the range as recommended by [@brown_predicting_2012]. Tree complexity was set to three to allow for second and third order interaction effects. The minimum number of observations required in the final nodes of each tree was three. A ten-fold cross-validation technique allowed us to determine the number of trees at which prediction error was minimized using the cross-validation deviance. Model performance was evaluated using the minimum estimated cross-validation deviance which maximized the estimated deviance explained.

\clearpage

## Results

### Rapture produces high quality genomic data for *Rana boylii*

To begin investigating the impact of river regulation on *R. boylii*, we collected frog tissue and buccal samples from 30 locations in six rivers representing three different flow impairment levels associated with hydropower generation. The three flow regimes assessed were: (1) hydropeaking, where flows are pulsed on most days from late spring through fall to provide electricity during peak-use hours and for recreational whitewater rafting; (2) bypass, which diverts river flows from an upstream portion of the basin to the downstream power generation facilities; and (3) unregulated, a largely natural flow regime where no upstream controls exist to regulate flows (Figure \@ref(fig:CH1F1map)). Flow data were obtained for each river reach using proximal USGS gaging stations (Table \@ref(tab:CH1T1)). We sampled a total of 345 *R. boylii* from sites in three major watersheds (Yuba, Bear, and American) in the northern Sierra Nevada of California (Figure \@ref(fig:CH1F1map), Table \@ref(tab:CH1T1)). The six study rivers share a similar Mediterranean climate, underlying geology, watershed aspect (west-slope), stream morphology (riffle-pool), and vegetative communities, but differ in the intensity of flow regulation [@steel_associating_2017]. Although river regulation occurs in all three of the study watersheds, both the North Yuba and North Fork (NF) American are unregulated whereas the Middle Fork (MF) American is the only river that has a hydropeaking flow regime (Figure \@ref(fig:CH1F1map)A). 


\begin{table}[!h]

\caption{(\#tab:CH1T2)Metadata for USGS gaging stations with current and historic data available for each study river}
\centering
\fontsize{11}{13}\selectfont
\begin{tabular}[t]{lllrr}
\toprule
Study Site & USGS Gage Number & Years of Record & Latitude & Longitude\\
\midrule
\addlinespace[0.3em]
\multicolumn{5}{l}{\textbf{North Yuba}}\\
\hspace{1em}North Yuba & 11413000 & 1931–Present & 39.52500 & -120.9369\\
\addlinespace[0.3em]
\multicolumn{5}{l}{\textbf{Middle Yuba}}\\
\hspace{1em}Middle Yuba & 11408550 & 1987–Present & 39.52194 & -120.5825\\
\hspace{1em}Middle Yuba & 11408700 & 1957–1966 & 39.43861 & -120.8111\\
\addlinespace[0.3em]
\multicolumn{5}{l}{\textbf{South Yuba}}\\
\hspace{1em}South Yuba & 11414250 & 1965–Present & 39.31861 & -120.6567\\
\hspace{1em}South Yuba & 11417000 & 1942–1972 & 39.36056 & -120.7706\\
\addlinespace[0.3em]
\multicolumn{5}{l}{\textbf{NF American}}\\
\hspace{1em}NF American & 11427000 & 1942–Present & 38.93611 & -121.0228\\
\addlinespace[0.3em]
\multicolumn{5}{l}{\textbf{Rubicon}}\\
\hspace{1em}Rubicon & 11433200 & 1959–1984 & 38.99250 & -120.7206\\
\hspace{1em}Rubicon & 11427765 & 1974–Present & 39.00027 & -120.7231\\
\addlinespace[0.3em]
\multicolumn{5}{l}{\textbf{MF American}}\\
\hspace{1em}MF American & 11433300 & 1958–2011 & 39.00611 & -120.7597\\
\hspace{1em}MF American & 11433500 & 1911–1986 & 38.91805 & -121.0142\\
\hspace{1em}MF American & OXB (PCWA)\textsuperscript{1} & 1997–Present & 39.00600 & -120.7600\\
\bottomrule
\multicolumn{5}{l}{\textsuperscript{1} PCWA=Placer County Water Agency, http://cdec.water.ca.gov/cdecstation2/?sta=OXB}\\
\end{tabular}
\end{table}

(ref:ch1fig1map) Sampling locations and flow characteristics. A) Map of sampling locations spread across six rivers. B) Comparison of annual mean daily discharge from 1981–2016 for three flow types. C) Comparison of hourly discharge in three different flow regimes in April through July 2012, Bypass (South Yuba), Hydropeaking (Middle Fork American), and Unregulated (North Fork American). See Table \@ref(tab:CH1T2) for USGS gaging station information.



\begin{figure}
\includegraphics[width=1\linewidth]{figure/ch1/fig_01_ac_map_hydrographs} \caption{(ref:ch1fig1map)}(\#fig:CH1F1map)
\end{figure}


To generate genetic data from the samples, we performed RAD Capture (a.k.a. Rapture) [@ali_rad_2016] on the samples by generating SbfI RAD libraries, capturing a subset of the RAD loci using 8,533 baits (see Methods), and sequencing the resulting library on an Illumina HiSeq. We then aligned the sequencing reads from each sample to a de novo RAD assembly (see Methods). The mean number of filtered alignments across all 345 samples was 324,928. For downstream analysis, we selected individuals that had greater than 100,000 alignments (n=277), which provided sufficient data to investigate population genetic attributes at broad and fine geographic scales (see below). *R. boylii* are cryptic, and often occur in low densities within the study area. Thus, we retained a minimum of three individuals per site, and the mean number of samples per site was approximately nine (Table \@ref(tab:CH1T1)). With genomic data, population genetic parameters can be accurately estimated from even low sample numbers [@hotaling_demographic_2018], and genomic analyses in non-model organism often use fewer loci [@narum_genotyping-by-sequencing_2013]. We conclude that the sequence data we obtained should be appropriate for population genetic analyses across our study area.

### Anomalous genetic pattern in highly regulated reach of Middle Fork American watershed

To assess *R. boylii* population structure across the collection locations, we used ANGSD [@korneliussen_angsd_2014] to discover 44,406 SNPs and perform principal component analysis (PCA; see Methods), which provides a dimensionless comparison of all samples. The first two principal components revealed four main groups corresponding to the Yuba, Bear, North Fork (NF) American, and Middle Fork (MF) American samples (Figure \@ref(fig:CH1F2pca)A). Unlike the Yuba watershed where all rivers clustered as one group, the two rivers within the American watershed (the NF American and MF American) were separated by both PC1 and PC2. Although the NF American watershed clustered closely with the adjacent Bear watershed, the MF American showed a surprisingly high degree of genetic differentiation from other locations (Figure \@ref(fig:CH1F2pca)A). These data suggest that there is less genetic differentiation between the NF American and the Bear watersheds, than between the NF and MF American watersheds. We conclude that measurements of overall genetic differentiation in *R. boylii* from our study area largely conform to watershed and geographic expectations, with the exception of the American watershed, which shows a surprisingly high degree of genetic differentiation between the North (unregulated) and Middle (hydropeaking) Forks.

(ref:ch1fig2pca) Principal component analysis of Rapture sequencing data. A) Northern Sierra Nevada (n=277) watersheds and regulation types; B) Unregulated NF American; C) and D) Hydropeaking MF American Reach.

\begin{figure}
\includegraphics[width=1\linewidth]{figure/ch1/fig_02_pca_combined_v2} \caption{(ref:ch1fig2pca)}(\#fig:CH1F2pca)
\end{figure}

To further investigate patterns of genetic variation within the American watershed, we performed two PCAs, one on samples from the NF American, and the other on samples from the MF American. The PCA of the NF American showed minimal differentiation among locations, with different study sites blending together and weak patterns of population structure (Figure \@ref(fig:CH1F2pca)B). In contrast, PCA of the MF American showed strong differentiation between sites (Figures \@ref(fig:CH1F2pca)C, \@ref(fig:CH1F2pca)D). The MF American PCA completely resolved all sites, with the first component (PC1) strongly differentiating the samples in the hydropeaking reach from all other sites in the MF American. This pattern may be due to the differential river regulation between the two rivers; the NF American is unregulated and has weak PCA differentiation, whereas the MF American has a higher level of river regulation and all sites form distinct genetic clusters, indicative of reduced gene flow among sites within the MF American.

### River regulation is the strongest predictor of genetic isolation with *R. boylii* in the Northern Sierra

To assess how patterns of genetic differentiation are associated with river regulation across our entire study area, we estimated pairwise F~ST~ [@wright_isolation_1943] between all collection locations within a river for all six rivers. We then plotted the scaled mean pairwise F~ST~ [mean F~ST~ / (1-mean F~ST~)]  [@rousset_genetic_1997] for each location against the mean river distance (the average distance along the river network from each collection location to every other location within that study river). Furthermore, each location was categorized by regulation level of closest mainstem location. While there was a clear relationship between F~ST~ and river distance (as shown by the slope of regression lines in Figure \@ref(fig:CH1F3fst)A), there was a striking pattern of elevated F~ST~ by regulation type (Figure \@ref(fig:CH1F3fst)A). Even the bypass regulation type showed a distinct pattern of elevated F~ST~ compared to the unregulated type. For instance, regulated rivers with locations separated by less than 10km had F~ST~ values comparable to unregulated locations separated by mean river distances over 30 km. Hydropeaking was the most extreme pattern of the three regulation types and showed highly elevated F~ST~ values with the steepest regression coefficient. The baseline F~ST~ or global mean increased by over 0.1 between the unregulated (mean F~ST~=0.141), and regulated locations (global mean for bypass F~ST~=0.256, hydropeaking F~ST~=0.278). This suggests a greater degree of isolation within sites in regulated river reaches compared with *R. boylii* populations in unregulated reaches, as larger F~ST~ values represent reductions in heterozygosity due to population subdivision [@slatkin_gene_1987]. We conclude *R. boylii* in regulated rivers show patterns of greater population isolation and loss of heterozygosity compared to frogs in unregulated locations.

To investigate the relative influence of river regulation compared to other covariates such as river distance on genetic differentiation (i.e. F~ST~), we used boosted regression tree (BRT) modeling. Covariates included flow regime alteration type, river distance, watershed variables derived from National hydrology data (NHD), topographic data, and allele frequency spectrum skew. We found flow regulation explained the greatest amount of variance in F~ST~ (Figure \@ref(fig:CH1F3fst)B). Thus, river regulation has a larger relative influence than mean river distance between sampling locations, which is often the most important factor influencing genetic differentiation [@rousset_genetic_1997; @slatkin_gene_1987; @wright_isolation_1943]. We conclude there is a pattern of isolation and limited connectivity between populations in regulated reaches.

(ref:ch1fig3fst) Relationship between river regulation and genetic differentiation in *R. boylii*. A) Mean pairwise F~ST~ vs. mean river distance for each location; B) Relative influence of variables on F~ST~ from boosted regression tree models.

\begin{figure}
\includegraphics[height=0.6\textheight]{figure/ch1/fig_03ab_fst_brt_cowplot_for_phd} \caption{(ref:ch1fig3fst)}(\#fig:CH1F3fst)
\end{figure}


\clearpage

### River regulation strongly correlated with decreasing genetic diversity in *R. boylii*

To investigate the association between river regulation and genetic diversity trajectory (stable, increasing, or decreasing), we summarized patterns of genetic variation using two estimators of $\theta$ ($4N\mu$): Tajima's $\theta$ ($\theta_\pi$) is based on the average number of pairwise differences [@tajima_evolutionary_1983] and Watterson’s $\theta$ ($\theta_S$) is based on the number of segregating sites [@watterson_number_1975]. These estimators are influenced by the demographic history of a population and provide information on the trajectory of changes in genetic diversity. When genetic diversity has been stable, these estimates are generally equal; but when genetic diversity has been increasing, $\theta_\pi > \theta_S$; and when genetic diversity has been decreasing, $\theta_S > \theta_\pi$. We found zero populations sampled within regulated watersheds had evidence of increasing genetic diversity (e.g., a $\theta_\pi - \theta_S$ that was less than zero) (Figure \@ref(fig:CH1F4theta)A). The regulated locations showed a clear trajectory of genetic diversity loss (Figure \@ref(fig:CH1F4theta)A, \@ref(fig:CH1F4theta)B). Three of the four hydropeaking locations had the highest values of $\Delta\theta$ ($\theta_\pi - \theta_S$), and the global mean was significantly different from other regulation types. Although some tributary populations within unregulated watersheds also showed signs of genetic diversity loss, the mean genetic diversity trajectory at unregulated locations was largely neutral (Figure \@ref(fig:CH1F4theta)B). This indicates populations in the northern Sierra Nevada which are already limited in number are losing genetic variation, and river regulation appears to be exacerbating these patterns. We conclude there is evidence of recent genetic diversity loss across populations in the regulated river systems, regardless of regulation type.

(ref:ch1fig4theta) Relationship between river regulation and genetic diversity trajectory in *R. boylii*. A) Assessment of genetic diversity trajectories using $\Delta\theta$ ($\theta_\pi - \theta_S$) for each sampling location; B) Boxplots of difference between $\theta_\pi - \theta_S$ and pairwise significance between regulation groups using a pairwise Wilcoxon rank sum test with bonferroni correction (P < 0.05). Negative values represent trends of increasing genetic diversity, positive values represent trajectories of diversity loss, values near zero are stable.

\begin{figure}
\includegraphics[height=0.8\textheight,scale=1.1]{figure/ch1/fig_04ab_theta_combined_for_phd} \caption{(ref:ch1fig4theta)}(\#fig:CH1F4theta)
\end{figure}

\clearpage

## Discussion

Although massive parallel sequencing (MPS) technologies have the potential to facilitate collection of high-quality genetic data in virtually any species, a number of challenges still remain for many species including low quality or non-existent reference genomes, large/complex/repetitive genomes, and high cost of processing/sequencing in studies with many samples. Amphibians are particularly challenging as many species have very large genome sizes [@nunziata_genomic_2017], for example, there are only two frog reference genome assemblies available as of 2018 [@hellsten_genome_2010; @sun_whole-genome_2015]. Our results demonstrate that Rapture [@ali_rad_2016] is a suitable method to rapidly and inexpensively discover a large number of loci in a frog species with a complex genome. In this study, we used new RAD sequencing and RAD capture (Rapture) methods [@ali_rad_2016] to generate high-quality genomic data suitable for discovering and genotyping many single nucleotide polymorphisms (SNPs) in *R. boylii*. Based on this dataset, we were able to successfully characterize patterns of genetic variation within *R. boylii* as well as design a set of RAD capture baits that can be used as a genetic monitoring resource for *R. boylii* (and likely other ranid species). This highlights that the collection of genetic information, even from large numbers of samples or in complex genomes, is no longer a limitation with current genomic methods such as RAD and Rapture.

Demographic connectivity is widely recognized as a fundamental driver of long-term population persistence [@fahrig_habitat_1985; @taylor_connectivity_1993]. Populations must adapt over time and connectivity is a major way to transfer genetic information. For example, previous studies have shown that adaptation can occur by spreading specific alleles across large geographic distances [@miller_conserved_2012; @prince_evolutionary_2017]. In many regulated river reaches in the Sierra Nevada, *R. boylii* now occur in isolated locations, breeding in tributaries rather than mainstem habitats. However, since these frogs have the potential to move long distances (@bourque_spatial_2008 documented *R. boylii* individuals that moved over 1 km in a day), the extent to which current population connectivity has been lost due to river regulation remains unknown. Examining pairwise F~ST~, revealed a major decrease in connectivity in populations in regulated systems, even with limited river regulation (i.e., bypass reaches). Usually isolation by distance patterns best describe variation in genetic data, yet the primary factor influencing genetic differentiation among these rivers is hydrologic alteration (Figure \@ref(fig:CH1F3fst)B). Thus, despite being able to move long distances, *R. boylii* have not been able to maintain population connectivity in regulated rivers. This demonstrates that even in species that can move relatively long distances and pass potential physical barriers (e.g., infrastructure such as dams, canals, and reservoirs likely do not represent true barriers to movement of *R. boylii*), loss of connectivity may still occur and can be revealed with genetic analysis. 

Genetic diversity is also a critical component for long-term population persistence because it is closely related to the evolutionary capacity for adaptation to environmental changes [@frankham_introduction_2002; @hoffmann_climate_2011; @ishiyama_differential_2015; @lande_role_1996]. In some cases, isolated populations can maintain genetic diversity when they are sufficiently sized [@whiteley_genetic_2010], however, species of conservation concern typically have small and/or declining populations and thus may be susceptible to genetic diversity loss [@krohn_conservation_2018]. Throughout the Sierra Nevada, *R. boylii* have largely disappeared from regulated mainstem rivers, but the extent to which existing populations have been able to maintain genetic diversity is unclear. Strikingly, our analysis revealed that every single population within the regulated watersheds exhibits a trajectory of genetic diversity loss. Thus, genomic analysis of molecular variation provides a powerful lens to discover and assess trajectories of genetic diversity.

Our analyses, using metrics that can serve as a reasonable proxy for genetic health of a population, does not bode well for the long-term persistence of *R. boylii* populations in regulated rivers in the Sierra Nevada. Many of these *R. boylii* populations are already losing genetic diversity and given their small size and reduced connectivity the effects of inbreeding will likely exacerbate their problems. *Rana boylii* have evolved in river systems with consistent hydrologic seasonality and predictability, despite inter-annual variation. Flow regulation has altered patterns of hydrologic seasonality and predictability in many watersheds [@kupferberg_effects_2012]. Long-term population persistence may still be possible if conservation efforts utilize methods that promote or maintain genetic diversity and increase population connectivity. For example, simulations by @botero_evolutionary_2015 demonstrated adaptation persisted in modeled populations through large environmental changes—if phenotypic strategies were appropriate before and after the change—but modeled populations declined rapidly when the current strategy was a mismatch to the current environment. Thus, *R. boylii* conservation efforts should focus on river reaches where flow management may provide opportunities to more closely mimic local natural flow regimes and improve hydrologic connectivity to prevent further genetic diversity loss.

## Conclusion

Detecting evolutionary responses to within- and among-year changes in an ecological or hydrological context has previously been difficult. However, utilizing genetic data can fill these gaps and provide a highly informative process for identifying the impacts of anthropogenic and environmental change on the process of adaptation [@botero_evolutionary_2015; @kahilainen_conservation_2014]. We demonstrate that an aquatic species that has adapted to local hydrology patterns shows poor genetic health (i.e., clear patterns of decreased connectivity and trajectories of genetic diversity loss). Our results highlight the potential impact of river regulation on aquatic organisms and their potential for long term persistence. In the future, similar genetic approaches could be used in many other contexts to explore the impacts of river regulation on aquatic organisms. Taken together, our results demonstrate that genetic monitoring can be a powerful tool for assessment of population health and should be a critical component of conservation management in aquatic organisms.

<!--chapter:end:01-chap1.Rmd-->


# Hybridization between two sympatric ranid frog species in the northern Sierra Nevada, California {#hybrids}

Placeholder


## Introduction
## Methods
### Sampling and DNA Extraction {#ch2samplecollection}
### Rapture Sequencing {#rapture2}
### PCA and Admixture
### F1 vs. F2 Test with Species Diagnostic SNPs {#f1vsf2}
### Demographic Modeling with fastsimcoal2
## Results
### Rapture produced high quality genomic data for both *R. sierrae* and *R. boylii*
### PCA shows strong separation between species and identifies putative hybrids
### Admixture shows two unknown individuals with equal *Rana* species ancestry 
### F1 vs. F2 test on hybrids
### Divergence times and migration rates
## Discussion
## Conclusion
### Acknowledgements

<!--chapter:end:02-chap2.Rmd-->


# Refining conservation unit boundaries of a sentinel stream-breeding frog (*Rana boylii*) using population genomics {#rangewide}

Placeholder


## Introduction
## Methods
### Sampling and DNA extraction  
### Generating high-quality sequencing data {#ch3rapture}
### Quantifying genetic structure
### Genetic differentiation and diversity estimates
## Results
### PCA and Admixture shows strong separation between California ecoregions
### F~ST~ shows strong divergence across regions
### Genetic variation is highest in the North-West and lowest in the East/ South-West clades
## Discussion and Conclusion
### Acknowledgements

<!--chapter:end:03-chap3.Rmd-->


# Appendix: Supplemental Tables & Code

Placeholder


### Supplemental Tables {#supptables}
### Code

<!--chapter:end:05-appendix.Rmd-->


# Colophon {-}

Placeholder



<!--chapter:end:98-colophon.Rmd-->


# References {-}

Placeholder



<!--chapter:end:99-references.Rmd-->

