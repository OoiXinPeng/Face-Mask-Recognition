# Face-Mask-Recognition
This is an individual project related to COVID-19 and face recognition. There are 2 objectives for this project:  
1. To detect people having their faces masked or not masked
2. To detect faces having their masks correctly worn or incorrectly worn

Progress:
- [x] Preprocess the data
- [x] Train the model
- [ ] Accept input from users

## Dataset
The [dataset](https://drive.google.com/drive/folders/1RgofnTbxkZneJTXsh1Dswglfl7NZRl0p?usp=sharing) is obtained from [FFHQ-dataset](https://github.com/NVlabs/ffhq-dataset) and [MaskedFace-Net](https://github.com/cabani/MaskedFace-Net). 

### Licenses
<b>In the following the licenses of the original [FFHQ-dataset](https://github.com/NVlabs/ffhq-dataset):</b>
The individual images were published in Flickr by their respective authors under either <a href=https://creativecommons.org/licenses/by/2.0/>Creative Commons BY 2.0</a>, <a href=https://creativecommons.org/licenses/by-nc/2.0/>Creative Commons BY-NC 2.0</a>, <a href=https://creativecommons.org/publicdomain/mark/1.0/>Public Domain Mark 1.0</a>, <a href=https://creativecommons.org/publicdomain/zero/1.0/>Public Domain CC0 1.0</a>, or <a href=http://www.usa.gov/copyright.shtml>U.S. Government Works</a> license. All of these licenses allow free use, redistribution, and adaptation for non-commercial purposes. However, some of them require giving appropriate credit to the original author, as well as indicating any changes that were made to the images. The license and original author of each image are indicated in the metadata.

<ul>
  <li>https://creativecommons.org/licenses/by/2.0/</li>
  <li>https://creativecommons.org/licenses/by-nc/2.0/</li>
  <li>https://creativecommons.org/publicdomain/mark/1.0/</li>
  <li>https://creativecommons.org/publicdomain/zero/1.0/</li>
  <li>http://www.usa.gov/copyright.shtml
</ul>

The dataset itself (including JSON metadata, download script, and documentation) is made available under <a href=https://creativecommons.org/licenses/by-nc-sa/4.0/>Creative Commons BY-NC-SA 4.0</a> license by NVIDIA Corporation. You can use, redistribute, and adapt it for non-commercial purposes, as long as you (a) give appropriate credit by citing our paper, (b) indicate any changes that you've made, and (c) distribute any derivative works under the same license.
https://creativecommons.org/licenses/by-nc-sa/4.0/

<b>The licenses of MaskedFace-Net dataset:</b> The dataset is made available under <a href=https://creativecommons.org/licenses/by-nc-sa/4.0/>Creative Commons BY-NC-SA 4.0</a> license by NVIDIA Corporation. 
You can use, redistribute, and adapt it for non-commercial purposes, as long as you 
<ol type="a">
<li> give appropriate credit by citing our papers: <ol type="1"><li>Adnane Cabani, Karim Hammoudi, Halim Benhabiles, and Mahmoud Melkemi, "MaskedFace-Net - A dataset of correctly/incorrectly masked face images in the context of COVID-19", Smart Health, ISSN 2352-6483, Elsevier, 2020, <a href=https://doi.org/10.1016/j.smhl.2020.100144>DOI:10.1016/j.smhl.2020.100144</a></li> <li> Karim Hammoudi, Adnane Cabani, Halim Benhabiles, and Mahmoud Melkemi,"Validating the correct wearing of protection mask by taking a selfie: design of a mobile application "CheckYourMask" to limit the spread of COVID-19", CMES-Computer Modeling in Engineering & Sciences, Vol.124, No.3, pp. 1049-1059, 2020, <a href=https://www.techscience.com/CMES/v124n3/39927>DOI:10.32604/cmes.2020.011663</a></li></ol></li>
<li> indicate any changes that you've made, </li>
<li>and distribute any derivative works under the same license. https://creativecommons.org/licenses/by-nc-sa/4.0/ </li>
</ol>

### Bibtex references
> Adnane Cabani, Karim Hammoudi, Halim Benhabiles, and Mahmoud Melkemi, "MaskedFace-Net - A dataset of correctly/incorrectly masked face images in the context of COVID-19", Smart Health, ISSN 2352-6483, Elsevier, 2020, <a href=https://doi.org/10.1016/j.smhl.2020.100144>DOI:10.1016/j.smhl.2020.100144</a> 

```
@Article{cabani.hammoudi.2020.maskedfacenet,
    title={MaskedFace-Net -- A Dataset of Correctly/Incorrectly Masked Face Images in the Context of COVID-19},
    author={Adnane Cabani and Karim Hammoudi and Halim Benhabiles and Mahmoud Melkemi},
    journal={Smart Health},
    year={2020},
    url ={http://www.sciencedirect.com/science/article/pii/S2352648320300362},
    issn={2352-6483},
    doi ={https://doi.org/10.1016/j.smhl.2020.100144}
}
```

>Karim Hammoudi, Adnane Cabani, Halim Benhabiles, and Mahmoud Melkemi,"Validating the correct wearing of protection mask by taking a selfie: design of a mobile application "CheckYourMask" to limit the spread of COVID-19", CMES-Computer Modeling in Engineering & Sciences, Vol.124, No.3, pp. 1049-1059, 2020, <a href=https://www.techscience.com/CMES/v124n3/39927>DOI:10.32604/cmes.2020.011663</a>

```
@Article{cmes.2020.011663,
    title={Validating the Correct Wearing of Protection Mask by Taking a Selfie: Design of a Mobile Application “CheckYourMask” to Limit the Spread of COVID-19},
    author={Karim Hammoudi, Adnane Cabani, Halim Benhabiles, Mahmoud Melkemi},
    journal={Computer Modeling in Engineering \& Sciences},
    volume={124},
    year={2020},
    number={3},
    pages={1049--1059},
    url={http://www.techscience.com/CMES/v124n3/39927},
    issn={1526-1506},
    doi={10.32604/cmes.2020.011663}
}
```

