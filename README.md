# Cropland Mapping

## Problem Statement
<p style="text-align: justify">In a global scenario still affected by severe income distribution imbalances and chronic famine in several communities, the accurate classification of cropland pieces is of utmost strategic and economic importance. As described in [1] reference below, crop maps play "<em>an important role in various applications such as crop inventories, crop insurance, yield estimation and the enforcement of quota limits</em>".</p>
<p style="text-align: justify">Remote sensing and geographic information systems (GIS) have been reliable tools in remote crop mapping. Remote sensors like radiometers and radars positioned in unmanned aerial vehicles and satellites enable a continuous, high quality, relatively reduced cost monitoring of the Earth surface use by agriculture, addressing specific issues inherent to the problem, like for example the dynamic changes of crop characteristics and growing stages over time. As the evaluation of such technologies is not a purpose of this work, readers are encouraged to consult the brilliant references cited for a high quality education on the subject.</p>

### Combining and processing optical and radar-based data for cropland classification
<p style="text-align: justify">Among remote sensing solutions, <b>optical</b> and <b>radar-based</b> sensing techniques demand special consideration when it comes to cropland classification. Furthermore, a combination of both has consistently led to high accuracy identification of crops of varied nature and in different development stages.</p>
<p style="text-align: justify">The dataset serving as the basis for this machine learning study, described in detail in Section 3, contains a large set of numerical features derived from remote sensing information assembled by two primary sources:</p>
<ul>
    <li style="text-align: justify">Optical information (actual images) was collected by RapidEye satellites;</li>
    <li style="text-align: justify">Radar-based information was collected by an Unihnabitated Aerial Vehicle Synthetic Aperture Radar (UAVSAR) system.</li>
</ul>
<p style="text-align: justify">As the amount and complexity of data gathered from such different sources over several time spans is inherently huge, <b>machine learning</b> plays a central role when it comes to the final classification purpose. The literature is vast and describes inumerous approaches and techniques to manipulate such information. The researchers cited in foreword have themselves assessed several solutions, stacked random forests in particular, with overall accuracies ranging from 90 to 96% for different stacking strategies. It has been noted though that some of the references are outdated, which suggests that the use of state-of-the-art classification engines - random forest and neural network classifiers - may lead to further metric improvements.</p>


## Objective
<p style="text-align: justify">Two major objectives are proposed for this study:</p>
<ol>
    <li style="text-align: justify">Assess the performance of scikit-learn's Random Forest Classifier;</li>
    <li style="text-align: justify">Investigate potential performance improvements that may be offered by an Artificial Neural Network (ANN).</li>
</ol>
<p style="text-align: justify">A third objective would enhance even more this exercise: the processing of actual RapidEye satellite images with computer vision learning engines - a convolutional neural network (CNN), for example - and the corresponding performance assessment. Future revisions of this work may incorporate such analysis, if and when such images are made available by the respective sources.</p>
