# UFPR-VC Dataset

The UFPR Vehicle Color (UFPR-VC) dataset was introduced in 2024 to address vehicle color recognition in more complex scenarios than those explored in previous studies. The dataset's construction and initial results from experiments using deep learning models are detailed in the paper *Toward Enhancing Vehicle Color Recognition in Adverse Conditions: A Dataset and Benchmark* [[PDF]]().

## About

The UFPR Vehicle Color (UFPR-VC) dataset contains 10,039 images of 9,502 distinct vehicles across various categories, including cars, vans, buses, and trucks. The images represent a wide range of real-world conditions, such as frontal and rear views, partial occlusions, diverse lighting situations, and nighttime scenes. Examples of these images are shown in Fig. 1.

<br>
<figure>
    <figcaption>
        <b>Fig. 1.</b> Examples of images from the UFPR-VC dataset, with the corresponding vehicle color annotations displayed above each image.
    </figcaption>
    <img src=./imgs/ufpr_vc_samples.png alt="samples from UFPR-VC dataset">
</figure>
<br>

The dataset's images were sourced from six public datasets collected in Brazil, originally created for automatic license plate recognition. These datasets include [OpenALPR-BR](https://github.com/openalpr/benchmarks/tree/master/endtoend/br/), [RodoSol-ALPR](https://github.com/raysonlaroca/rodosol-alpr-dataset), [SSIG-SegPlate](https://doi.org/10.1117/1.JEI.25.5.053034), [UFOP](https://doi.org/10.1109/ICSMC.2011.6084108), [UFPR-ALPR](https://web.inf.ufpr.br/vri/databases/ufpr-alpr/), and [Vehicle-Rear](https://github.com/icarofua/vehicle-rear). The original images underwent preprocessing and selection procedures to standardize them and identify those suitable for vehicle color recognition.

The images cover eleven distinct vehicle colors: beige, black, blue, brown, gray, green, orange, red, silver, white, and yellow. The class distribution of the dataset is presented in Fig. 2. Annotations for over 90% of the vehicles were validated using information obtained from the corresponding license plate annotations in the original datasets.

<br>
<figure>
    <figcaption>
        <b>Fig. 2.</b> Distribution of vehicle colors in the UFPR-VC dataset.
    </figcaption>
    <img src=./imgs/class_dist.png alt="UFPR-VC class distribution">
</figure>
<br>

Regarding privacy concerns, it is important to note that since the data originates from Brazilian automatic license plate recognition datasets, the license plates are associated with vehicles only, and no public information about vehicle drivers or owners is available.

## How to obtain

The UFPR-VC dataset is available exclusively for academic research and is provided free of charge to researchers affiliated with educational or research institutions for **non-commercial use**.

To access the dataset, please review the [**license agreement**](./pdfs/), complete it, and return it to the first author at ([gelima@inf.ufpr.br](mailto:gelima@inf.ufpr.br)). Make sure to send your request from a valid university email account (e.g., .edu, .ac, or similar). You can expect to receive a download link within 1-5 business days. 

Please note that failure to follow these instructions may result in no response.


## Citation

If you use the UFPR-VC dataset in your research, please cite the paper:

* Paper [[arXiv]]().

```
@inproceedings{key,
  title = {},
  author = {},
  year = {},
  month = {},
  booktitle = {},
  volume = {},
  number = {},
  pages = {},
  doi = {},
  isbn = {},
  issn = {}
}
```

## Contact

For any questions or comments, please contact Gabriel E. Lima ([gelima@inf.ufpr.br](mailto:gelima@inf.ufpr.br)).
