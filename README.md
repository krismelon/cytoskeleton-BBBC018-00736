## cytoskeleton-BBBC018-00736

**Student ID**: 202303468

**Chosen Phenotype**: Peripheral Actin

**Image-field ID**: 00736

**Actin filename**: 00736-actin.DIB

**DNA filename**: 00736-DNA.DIB

## Dataset

BBBC018 dataset was used for this activity, containing the fluorescence microscopy images of HT29 human colon cancer cells. The actin-stained images were used to examine cell structure, while the DNA-stained images helped located the nuclei and observe chromosome arrangement. 

BBBC018 download link: https://bbbc.broadinstitute.org/BBBC018

## Fiji Steps

<img width="910" height="850" alt="image" src="https://github.com/user-attachments/assets/b1a52cd4-94af-424d-8cbc-78d56d379455" />

**_Figure 1_**. The image shows Fiji Downloads webpage where I chose x86-64 US for Windows.

<img width="640" height="852" alt="image" src="https://github.com/user-attachments/assets/119549aa-766e-4386-9b8b-6b4a5b929abc" />

**_Figure 2_**. Figure 1. Example fluorescence images of HT29 human colon cancer cells showing different phenotypes, including metaphase, prophase, and anaphase/telophase, along with variations in cell shape and actin distribution.

<img width="741" height="90" alt="image" src="https://github.com/user-attachments/assets/0ad375b2-49f9-42df-af35-561bd82d963c" />

**_Figure 3_**. Downloaded and extracted BBBC018 image dataset ZIP file, containing the fluorescence images for the cytoskeleton and cell morphology analysis.

<img width="740" height="82" alt="image" src="https://github.com/user-attachments/assets/7db13a21-be23-45c6-8c8c-9b438e19ac38" />

**_Figure 4_**. Downloaded and then extracted of the Fiji file. 

<img width="580" height="1072" alt="image" src="https://github.com/user-attachments/assets/89eae45f-568b-4147-a5d4-b7d3ff5cc5d9" />

**_Figure 5_**. Opening the Bio-Formats import option in Fiji/ImageJ to load the actin fluorescence image for further examination.

<img width="685" height="517" alt="image" src="https://github.com/user-attachments/assets/fdabbf55-084f-4c8b-849c-94d4dac7791a" />

**_Figure 6_**. The extracted BBBC018 dataset viewed in Fiji/ImageJ, showing the fluorescence images available for each field and their corresponding staining channels for selecting images to study cell morphology.

<img width="1447" height="777" alt="image" src="https://github.com/user-attachments/assets/ef4ef738-b8eb-4d39-9fe3-4bb4b073c5e5" />
<img width="360" height="560" alt="image" src="https://github.com/user-attachments/assets/3842644e-3898-4ab8-bba9-3872d70913e7" />

**_Figure 7_**. Configuring the measurement options in Fiji/ImageJ to record the area, average gray value, shape descriptors, and cell labels. These measurements were used to evaluate the size, actin signal intensity, and shape characteristics of the five chosen cells.

<img width="283" height="312" alt="image" src="https://github.com/user-attachments/assets/2cbda933-01fc-498e-afbc-544bedd73f69" />
<img width="510" height="152" alt="image" src="https://github.com/user-attachments/assets/f8ad0e86-967e-45ca-9033-0008dd55c231" />
<img width="162" height="205" alt="image" src="https://github.com/user-attachments/assets/bd185f20-95ea-489c-8ced-4222f8014691" />

**_Figure 8_**. Five cells were outlined in Fiji/ImageJ using the freehand selection tool and ROI Manager. The resulting data included each cell’s area, mean gray value, and circularity, which were used to examine differences in cell size, shape, and actin staining intensity.

## Plot

<img width="900" height="650" alt="actin_intensity" src="https://github.com/user-attachments/assets/7cb3eb87-063f-4cef-b8b2-ccdf7bdbe738" />

**_Figure 9_**. The bar graph compares the mean actin fluorescence intensity of five cells from image 00736. Cell 5 recorded the strongest signal, whereas Cell 2 showed the weakest, indicating variations in actin fluorescence levels among the selected cells.

<img width="900" height="650" alt="area_vs_circularity" src="https://github.com/user-attachments/assets/b9b60b02-8420-4f43-a9b4-b7ef1ae72901" />

**_Figure 10_**. The scatter plot illustrates the relationship between cell area and circularity in five cells from image 00736, classified under the Peripheral actin phenotype. Cell 1 had the greatest area, while Cell 5 showed the highest circularity, highlighting the differences in size and shape among the measured cells.

## Questions and Answers

**1. Which specific phenotype did you choose, and what visible features support that choice?**

- I chose the Peripheral Actin phenotype using image field 00736. In the actin image, the cells clearly show a bright band of staining around their outer borders with a darker interior. This distinct ring pattern highlights the actin gathered at the cell margins and outlines each individual cell.

2. Were your five cells mostly round or elongated? Refer to your circularity and aspect-ratio results.

- Based on my results, it shows that the five measured cells exhibit a predominantly round shape rather than an elongated one. Circularity metrics span from 0.632 up to 0.871, while aspect ratios remain near 1.0 (ranging between 1.039 and 1.302). For example, Cell 5 registered the highest circularity score of 0.871 with a total area of 338 px², whereas Cell 1 was the largest at 2,609 px² with a circularity of 0.789. Because aspect ratios stayed low and circularity scores remained elevated, none of the traced cells display a narrow or stretched morphology.

3. What role does actin play in maintaining cell shape and in cell movement (Karp Chapter 9)?

- Actin filaments maintain structural integrity by constructing a supportive cortical network underneath the plasma membrane that resists external physical forces. In cellular motility, actin polymerization drives forward protrusion at the leading edge to form structures like lamellipodia, while actomyosin-mediated contraction at the trailing edge draws the rest of the cell body forward.
   
4. Why can a single fixed fluorescence image NOT show how fast a cell moves?

- A single fixed fluorescence image only captures a static snapshot of a cell at one specific point in time. Calculating migration velocity requires tracking displacement across a measured time interval, which necessitates dynamic live-cell time-lapse recording rather than a single fixed image.
