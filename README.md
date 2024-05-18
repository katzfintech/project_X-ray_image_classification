# Project_X-ray_image_classification
# Executive Summary
&nbsp; Tuberculosis (TB) is a contagious illness caused by Mycobacterium tuberculosis bacteria, and it stands as the primary cause of death from a single infectious agent. Fortunately, TB can be effectively treated with antimicrobial medications. Early diagnosis, followed by appropriate treatment, is crucial for curing this potentially deadly disease [1]. In clinical practice, experienced physicians examine chest radiographs to detect TB, but this process is time-consuming and subjective. Consequently, there are inherent inconsistencies in disease diagnosis through radiographs, and TB images may be mistaken for other diseases with similar radiological patterns [2]. Such misclassifications can result in incorrect treatment, worsening patient health. Moreover, there's a shortage of trained radiologists in low-resource countries, particularly in rural areas. In light of the study, it is also worth noting that the healthcare industry is extremely different from other industries as it is a high priority industry where customers are willing to pay a higher price for higher quality.<br>
&nbsp; To address these challenges, computer-aided diagnosis (CAD) systems offer a promising solution for mass TB screening by analyzing chest X-ray images. Among the various deep learning techniques, convolutional neural networks (CNNs), along with the accessibility of large-scale labeled datasets have emerged as a powerful tool for image classification and are widely embraced by the research community [3].<br>
&nbsp; The dataset utilized in this study includes 3,500 normal chest X-ray images and 700 tuberculosis-positive images sourced from the National Library of Medicine and the National Institute of Allergy and Infectious Diseases. This dataset has been used in a paper published in IEEE Access [4]. <br>
&nbsp; In this experimental study, we explored multiple approaches to develop models for image classification. We constructed deep neural network (DNN) models with varying numbers of hidden layers, ranging from DNN1 to DNN4, and convolutional neural network (CNN) models with different architectures, including a basic CNN model and another with dropout regularization. <br>
&nbsp; Additionally, we incorporated transfer learning by utilizing a pre-trained model, specifically InceptionV3 and DenseNet201. Through thorough experimentation and evaluation, we identified the best-performing model as the CNN model with one Dropout layer before output, achieving a high validation accuracy of 0.996. This result shows the effectiveness of using the model for image classification tasks, demonstrating the ability to capture complex patterns and features in the data.
# Bibliography
[1] World Health Organization. (2023, November 7). Tuberculosis (TB). World Health 
Organization. https://www.who.int/news-room/fact-sheets/detail/tuberculosis <br><br>	
[2] Maheswari, B. U., Sam, D., Mittal, N., Sharma, A., Kaur, S., Askar, S. S., & Abouhawwash, 
M. (2024). Explainable deep-neural-network supported scheme for tuberculosis detection 
from chest radiographs. BMC medical imaging, 24(1), 32. https://doi.org/10.1186/s12880-024-01202-x<br><br>
[3] Oloko-Oba M and Viriri S (2022) A Systematic Review of Deep Learning Techniques for 
Tuberculosis Detection From Chest Radiograph. Front. Med. 9:830515. doi: 10.3389/fmed.2022.830515<br><br>
[4] Tawsifur Rahman, Amith Khandakar, Muhammad A. Kadir, Khandaker R. Islam, Khandaker 
F. Islam, Zaid B. Mahbub, Mohamed Arselene Ayari, Muhammad E. H. Chowdhury. (2020) "Reliable Tuberculosis Detection using Chest X-ray with Deep Learning, Segmentation and Visualization". IEEE Access, Vol. 8, pp 191586 - 191601. DOI. 10.1109/ACCESS.2020.3031384.
