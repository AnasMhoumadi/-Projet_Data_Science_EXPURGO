# -Projet_Data_Science_EXPURGO
# EXPURGO : détection de déchets
![image](https://user-images.githubusercontent.com/99479766/166452513-9f9d8f6d-26bf-44b4-ac41-35be0d961980.png)
#  Global description
Expurgo is a webapp wich allows to map waste thanks to trash detection model trained with taco dataset and yolov4 using google colab and roboflow for annotation. There is an interactive map in which you can see the locations of the different trash object. Furthermore, there is a dashboard made with collected data which rises people awareness towards importance of waste collection.
# Prerequisite
python 3.8
# Installation


    git clone https://github.com/WilfriedPonnou/Projet-Data-Science-EXPURGO.git
    pip install -r requirements.txt
    wget --load-cookies /tmp/cookies.txt "https://docs.google.com/uc?export=download&confirm=$(wget --quiet --save-cookies /tmp/cookies.txt --keep-session-cookies --no-check-certificate 'https://docs.google.com/uc?export=download&id=12Gvkfy1AzrLOx4vR1d6wScYXJv6iBuMi' -O- | sed -rn 's/.*confirm=([0-9A-Za-z_]+).*/\1\n/p')&id=12Gvkfy1AzrLOx4vR1d6wScYXJv6iBuMi" -O custom-yolov4-detector_best.weights && rm -rf /tmp/cookies.txt
    
Or download this file and add it to the repository, for the last step: https://drive.google.com/file/d/12Gvkfy1AzrLOx4vR1d6wScYXJv6iBuMi/view?usp=sharing

<!--endsec-->
# Run Expurgo webapp
      streamlit run streamlit_webapp.py
      
  Let's Do This

<p align="center">
  <img align="center" width="30%" src="https://media.giphy.com/media/elCqBPvwgchbiC3AFs/giphy.gif" />
</p>



