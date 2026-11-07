# Cytoskeleton and Cell Morphology #

## Activity Information ##
**Student ID:** 202303451

**Chosen phenotype:** Actin dots

**Image ID:** 07316

**DNA Filename:** 07316-DNA.DIB

**Actin Filename:** 07316-actin.DIB

**Dataset page:**  https://bbbc.broadinstitute.org/BBBC018

**Dataset downlink link**  https://data.broadinstitute.org/bbbc/BBBC018/BBBC018_v1_images.zip

## Fiji Steps ##

Step 1. The files 07316-actin.DIB and 07316-DNA.DIB were imported into Fiji through File > Import > Bio-Formats.

Step 2. Under Analyze > Set Measurements, the options Area, Mean Gray Value, Shape Descriptors, and Display Label were selected, while Limit to Threshold was left unchecked.

Step 3. The ROI Manager was opened through Analyze > Tools > ROI Manager.

Step 4. Five cells were outlined in the actin image using the polygon selection tool, with the DNA image serving as a reference for identifying the nuclei.

Step 5. Each traced cell was added to the ROI Manager by pressing T, then measured by pressing M.

Step 6. The Results table was exported as data/fiji_results_emperado - Sheet1.csv, while the image showing the traced cells was saved as figures/measured_cells.png. The original DIB files remained unchanged.

## Fiji Results ##

| No. | Label | Area | Mean Gray Value | Circularity | Aspect Ratio | Roundness | Solidity |
|---|---|---:|---:|---:|---:|---:|---:|
| 1 | 07316-actin.DIB:0319-0329 | 221 | 1046.946 | 0.914 | 1.068 | 0.937 | 0.980 |
| 2 | 07316-actin.DIB:0305-0345 | 222 | 1003.950 | 0.872 | 1.130 | 0.885 | 0.998 |
| 3 | 07316-actin.DIB:0356-0477 | 264 | 1320.258 | 0.891 | 1.033 | 0.968 | 1.000 |
| 4 | 07316-actin.DIB:0046-0462 | 255 | 714.627 | 0.894 | 1.112 | 0.899 | 0.975 |
| 5 | 07316-actin.DIB:0062-0443 | 412 | 1169.915 | 0.848 | 1.030 | 0.971 | 0.986 |

## Cell Measurement Results ##

| Phenotype  | Image ID | Cells Measured | Mean Area (px²) | Mean Circularity | Mean Aspect Ratio | Mean Actin Signal |
|------------|----------|----------------|-----------------|------------------|-------------------|-------------------|
| Actin dots | 07316    | 5              | 274.8           | 0.8838           | 1.0746            | 1051.1392         |

Five cells from image 07316 were analyzed under the Actin dots phenotype. The cells had a mean area of 274.8 px², mean circularity of 0.8838, mean aspect ratio of 1.0746, and mean actin signal of 1051.1392. These results indicate generally rounded cell shapes with relatively consistent proportions and measurable actin intensity.

## Figures ##

<img width="688" height="654" alt="image" src="https://github.com/user-attachments/assets/fe5cca3c-d24c-4c1a-bb18-1a19ca710dc1" />

**Figure 1.** Shows the traced cells using fiji

<img width="900" height="650" alt="image" src="https://github.com/user-attachments/assets/a3978cb2-80b2-4dea-8505-c5246c3ef175" />

**Figure 2.** Cells 1–4 had smaller areas (221–264 px²) and higher circularity values (0.872–0.914), while Cell 5 had the largest area (412 px²) and lowest circularity (0.848), suggest that that the larger cells tended to have less rounded shapes.

<img width="900" height="650" alt="image" src="https://github.com/user-attachments/assets/08935b5c-e898-4071-80be-89cb7cb99810" />

**Figure 3.** Cell 3 had the highest actin signal, while Cell 4 had the lowest. Cells 1, 2, and 5 showed relatively similar actin signals.

## Results Explained ##

**1. Which specific phenotype did you choose, and what visible features support that choice?**

I chose the actin dots phenotype because the cells showed distinct, dot-like actin fluorescence patterns rather than a uniform distribution.

**2. Were your five cells mostly round or elongated?**

The five cells were mostly round, with a mean circularity of 0.8838 and a mean aspect ratio of 1.0746, indicating shapes that were close to circular rather than elongated.

**3. What role does actin play in maintaining cell shape and in cell movement?**

Actin forms microfilaments that support the cell's structure and help maintain its shape. It also drives cell movement by forming protrusions and generating forces that allow the cell to move.

**4. Why can a single fixed fluorescence image NOT show how fast a cell moves?**

A fixed fluorescence image captures the cell at only one point in time. It cannot show changes in cell position or movement over time, which are needed to measure movement speed.

# Data Credit #

**We used image set BBBC018v1 from the Broad Bioimage Benchmark Collection (Ljosa et al., NatureMethods, 2012*


