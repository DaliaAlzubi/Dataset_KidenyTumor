# (KAUH Dataset) Kidney CT Dataset 2021

This dataset contains **8,400 abdominal CT images** collected from **kidney patients** with a variety of conditions, including:

- Kidney tumors
- Renal stones
- Renal cysts
- Other abnormalities

There are **no segmentation masks** included with this dataset.

## 🗂️ Dataset Download

You can download the full dataset from the link below:

🔗 [Download Kidney CT Dataset (Drive)] (https://drive.google.com/file/d/1uWCZrubp0qkzTVIZgI8wc0m8N2yeeWA4/view?usp=sharing)
- 70 images per patient, covering 120 patients. Image files are ordered by patient ID from 1 to 120. A metadata Excel file is provided, which may be helpful for segmentation tasks (e.g., identifying tumor regions or other annotations) (https://drive.google.com/file/d/1ZX8cOD829uxfPczOCBODaFmel9NwABJK/view?usp=sharing) 
  
## 📌 Dataset Details
- **Dataset name**: (**KAUH**)
- **Image Size:** 512×512 pixels
- **Format:** JPEG (.jpg)
- **Preprocessed:** Converted from DICOM to JPEG
- **Collected by:** Dalia Alzu'bi
- **Collected from:** King Abdullah University Hospital (**KAUH**), Jordan

## ⚠️ Important Notes
- This dataset does **not contain any patient-identifiable information (PHI)**.
- Use of this dataset must comply with **ethical standards** and **data protection regulations**.

## 📄 License
**Ethical Approval**
The dataset used in this master thesis, *Kidney Tumor Detection and Segmentation in Computed Tomography Scans using Deep Learning Models*, is based on **kidney CT scans** collected **after approval from the Institutional Review Board (IRB)** of **King Abdullah University Hospital (KAUH)**, Jordan. The approval order number is **137-2021**, and the scans were withdrawn from the hospital’s database for cases of renal masses, as performed by the **CT scan service** in **2021**.

---

## 📚 References

- Alzu'bi, Dalia, et al. "Kidney tumor detection and classification based on deep learning approaches: a new dataset in CT scans." *Journal of Healthcare Engineering* 2022, Volume 2022, Article 3861161. [DOI: 10.1155/2022/3861161](https://www.hindawi.com/journals/jhe/2022/3861161/)

- Gharaibeh, Maha, et al. "Radiology imaging scans for early diagnosis of kidney tumors: a review of data analytics-based machine learning and deep learning approaches." *Big Data and Cognitive Computing* 2022, Volume 6, Issue 1, Article 29. [DOI: 10.3390/bdcc6010029](https://www.mdpi.com/2509-4148/6/1/29)

- Alzu'bi, Dalia, et al. "Logistic regression classification for assessing the risk of kidney tumor." *2023 2nd International Engineering Conference on Electrical, Energy, and Artificial Intelligence (EICEEAI)*, 2023, IEEE, pp. 1-9.

---

## 📝 Citations

```bibtex
@article{alzu2022kidney,
  title={Kidney tumor detection and classification based on deep learning approaches: a new dataset in CT scans},
  author={Alzu’bi, Dalia and Abdullah, Malak and Hmeidi, Ismail and AlAzab, Rami and Gharaibeh, Maha and El-Heis, Mwaffaq and Almotairi, Khaled H and Forestiero, Agostino and Hussein, Ahmad MohdAziz and Abualigah, Laith},
  journal={Journal of Healthcare Engineering},
  volume={2022},
  number={1},
  pages={3861161},
  year={2022},
  publisher={Wiley Online Library}
}
