# huawei-watch-face-maker
huawei-watch-face-maker


1. Extract some watchFace do you want by `watchface_extractor.py` and Needed `Pillow` python library first
        
        pip install Pillow

        python watchface_extractor.py input_file.hwt [output_directory]

        
        Example: 
        python watchface_extractor.py watchface.hwt extracted_images


2. Using theme Studio from Huawei to make new face from extract resourced

3. Using Huawei heath Mod Version to import to your watch.