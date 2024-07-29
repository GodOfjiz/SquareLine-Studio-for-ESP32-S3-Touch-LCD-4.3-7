Feel Free to Download and Use the library

-Current Issue: Export Issue with SquareLine Studio
-Fix: When exporting:      
      1) Select "Export->Create Template Project"      
      2) It will open up the file manager, save to your desired location      
      3) After Confirming, the file manager will pop for UI export, please save at "Board Name"->__ui_project_name__->main->ui      
      4) After that you will see some errors in Squareline Studio but you don't have to worry as the files have been exported      

Note: After Exporting, I would suggest to rename __ui_project_name__ to your desired project name

How to get started:      
1)Install ESP_IDF:      
        -Install ESP_IDF by following "https://www.waveshare.com/wiki/ESP32-S3-Touch-LCD-4.3"

2)Install my library for Squareline Studio:      
        -Download my libray by cloning or as zip      
        -Rename folder to the name of the board that you desire (e.g. Waveshare Touch_LCD)      
        -Go to the folder where the boards SquareLine stores      
                Windows: C:\Users\USERNAME\Documents\SquareLine\boards      
                Linux:~/SquareLine/boards      
                MacOS: Users\USERNAME\SquareLine\boards      
        -After that, open SquareLine Studio and the board should be there under Espressif          
      Note: You can leave it as default or change the variable of the board description in SquareLine Studio at by editing the .slb file      
            group: Espressif                 // Where the board is stored      
      For more info go to "https://docs.squareline.io/docs/obp/"      

      3)Change your partition for export in ESP-IDF
      ![ESP-IDF Partition Setting](https://github.com/user-attachments/assets/bf28fc49-3217-4c88-a07c-b1d6eb7eca70)

      
    

