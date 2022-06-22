# Classify Oldest Surviving Buildings in the World

### Scraping Data, Image Classification Using CNN, and Deploy Model with **FLASK API** 

________

We'll Scrape the Data From Google photos, and then build a CNN Model using Keras to use it classifying thousands of pictures in sixteen different categories, and Finaly we will make Application by using the FLASK API to Deploy the Model. 

### **About Dataset**

#### **Context**
This is image data of Oldest Surviving Buildings In the world.

#### **Content**
We will Scrape around +4k RGB images of size 150x150 distributed under 16 different categories.


{'Colosseum'                    -> 0,

'Temple of Garni'              --> 1,

'Dun Carloway'                 --> 2,

'Ruwanwelisaya'                --> 3,

'Great Wall of China'          --> 4,

'Great Wall of China'          --> 5,

'Dhamek Stupa'                 --> 6,

'Sanchi Stupa'                 --> 7,

'Thracion Tomb of Kazanlak'    --> 8,

'Naveta d'Es Tudons'           --> 9,

'Chogha Zanbil'               --> 10,

'Pyramids of Giza'            --> 11,

'Bent Pyramid'                --> 12,

'Pyramid of Djoser'           --> 13,

'Dolmens of North Caucasus'   --> 14,

'Ggantija'                    --> 15  }

The Train, Test and Prediction data is separated in each zip files. There are around 2.5k images in Train, 1k in Test and 500 in Prediction.
_____

### Test Acc after Augmentation: **`79.5 %`**
### Test Loss: **`0.64`**
____

![download](https://user-images.githubusercontent.com/44786324/175093351-db73ef6c-51f0-48d7-a0b0-793d136429d8.png)
![download (1)](https://user-images.githubusercontent.com/44786324/175093399-6b9611bc-a4f0-4a7b-b709-e9708c484638.png)
![download (2)](https://user-images.githubusercontent.com/44786324/175093482-2821759c-5604-44f2-8810-9f2d10e7fd8c.png)
![download (3)](https://user-images.githubusercontent.com/44786324/175093535-ba0da169-3e9e-4ad3-b1ab-6271de5d4359.png)

____
**Application**

![image](https://user-images.githubusercontent.com/44786324/175096230-14a519cb-f187-48a6-9a96-9809027b52a1.png)
![image](https://user-images.githubusercontent.com/44786324/175096751-949811d5-4800-4bee-bb90-883dd2182ca9.png)

____
