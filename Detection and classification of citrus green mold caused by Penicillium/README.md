# Paper summary
#
[image1]: ./2.png "frst"
[image2]: ./1.png "second "
[image3]: ./3.JPG "third "



**Detection and classification of citrus green mold caused by**  **Penicillium digitatum**  **using multispectral imaging:**

**BACKGROUND :**  
Fungal decay is a prevalent condition that mainly occurs during transportation of products to consumers (from harvest to consumption) and adversely affect post-harvest operations and sales of citrus fruit. There are a variety of methods to control pathogenic fungi including UV-assisted removal of fruit with suspected infection before storage, which is a time-taking task coupled with human health risks. Therefore, it is essential to adopt efficient dependable alternatives for early decay detection. In this paper detection of orange decay caused by Penicillium genus fungi using spectral imaging, a novel automated inspection technique for agricultural products, was examined.


**Important definitions :**

**Reflectance of the surface** of a material is its effectiveness in reflecting radiant energy. It is the fraction of incident electromagnetic power that is reflected at an interface. The reflectance spectrum or spectral reflectance curve is the plot of the reflectance as a function of wavelength.

![alt text][image1]


Link:[https://en.wikipedia.org/wiki/Reflectance](https://en.wikipedia.org/wiki/Reflectance)


**NDVI Cameras**

Normalized Difference Vegetation Index (NDVI) is a measurement of the amount of live vegetation in an area and is commonly used for agricultural assessment

NDVI is a simple metric which indicates the health of vegetation. When near infrared hits the leaf of a healthy plant it is reflected back into the atmosphere. As the amount of chlorophyll produced in a plant decreases less near infrared is reflected. This can be used to see the overall health of a crop. The NDVI algorithm compares the reflected intensities of near infrared (NIR) and visible light
![alt text][image2]

Link : [https://support.dronedeploy.com/docs/ndvi-cameras-for-drones](https://support.dronedeploy.com/docs/ndvi-cameras-for-drones)


**RESULTS** : The reflectance parameter (including mean reflectance), and reflectance distribution parameters of surface (including standard deviation and skewness) were extracted from decayed and rotten regions of infected samples and the healthy regions of non-infected samples. The classification accuracy of rotten, decayed and healthy regions at four and five days after fungal inoculation was 98.6 % and 100 % using the mean values and skewness of 500 nm, 800 nm and 900 nm spectra and MNDVI.

**CONCLUSION: Comparison results between healthy and infected samples showed that early real-time detection of Penicillium digitatum using multispectral imaging was possible within the near infrared (NIR) range.**

**Note :** after the seventh day the decayed regions can be visible to naked eye, so early detection is in the (4,5,6) days after infection OR within the 3 days before decayed regions can be visible to naked eye 

**Detaied Information :** 
**Introduction:**
One of the most important post-harvest pathologic diseases of citrus fruit is the green mold caused by Penicillium digitatum fungus. It spreads through pores and wounds on a number of skin oil glands. If suitable temperature and moisture conditions are available, it creates watery stains on the fruit peel that would further create white mycelia. When stain sizes reach 2.5 cm to 5 cm, the production of olive-green spores begins. The rot gradually spreads, and rottenness covers a major part of or the whole fruit.
 To explain the terms rotten and decayed, the stages of fungi growth are expressed as follows: 
first, Penicillium digitatum fungi spreads though pores and wounds on a number of skin oil glands, then it creates watery stains on the fruit peel that would further create white mycelia. When the stain size reaches 2.5 cm to 5 cm in diameter, the production of olive-green spores begins.While the expansion of decayed region, the rotten region also is pushed out and spreads; this means healthy regions of peel becomes rotten, then white and then green.

This rot can be controlled by ensuring suitable conditions with low temperature and moisture content, which can be achieved by using proper warehouse ventilation, removal of fruit with suspected infection, fungicide-drenched fruit wrapping papers, fungicide solution baths for fruit, and sterilizing the warehouse and boxes.UV light can be also used to improve fruit resistance to green decay (researches were shown that UV-C is able to induce resistance of fruits and vegetables to postharvest storage rots  and to delay the ripening process extending the shelf life of fruits and vegetables) 

spectral imaging has been shown to be an effective method for quality assessment of agricultural products and can detect fruit with fungal infection. Peel defects have different spectral reflectance in certain segments of the electromagnetic spectrum,1 thus spectral imaging has been adopted in the literature to detect and distinguish peel defects of citrus fruit.

 NIR spectroscopy (NIRS) was used  for early detection of penicillium rot and Alternaria citri in navel oranges.Results showed that the reflectance spectrum of the infected tissues at 1050 nm was lower than the intact area. This is probably due to the fact that fungal sporulation of fruit peel extracts the intracellular fluid leading to water build-up in the infected tissue and its softening. At the same time, the fluid absorbs the NIR spectrum, reducing the IR-range reflectance in the infected area.
 
It can be concluded that although green mold detection of oranges using multispectral imaging has been studied, we can reduce the number of bands which would make real-time work possible. So in this study we consider four spectrum and a spectral index for decay detection using multispectral imaging.


A proper multispectral imaging system capable of capturing images from spherical or spheroidal shapes (oranges) should be first developed in order to detect orange green mold by multispectral imaging. The samples should be then inoculated with P. digitatum fungi. Finally, imaging should be done from the first possible day until the inoculation is clearly visible to naked eye, and spectral information should be extracted from images for analysis. These steps are fully explained in rest of the paper.


**Spectral Imaging System:**
Find system installiation details in the paper 

To extract spectral information, the images captured by the multispectral imaging system were used. The effects of lamp lighting variations were removed by calibrating the raw images. so a reference surface with 100 % reflectance was used.And a Calibration equation is used.

Once images were calibrated, the statistical parameters (such as mean, standard deviation and skewness) were extracted from pixels relating to rotten and decayed parts at different stages as shown below. These parameters were computed in MATLAB. For each region, a mean spectral reflectance value was obtained for 500 nm, 700 nm, 800 nm and 900 nm wavelengths as well as for the spectral index MNDVI.

![alt text][image3]


**Results**
Healthy and infected skin regions of both orange varieties had different reflectance,find more details in the paper 
