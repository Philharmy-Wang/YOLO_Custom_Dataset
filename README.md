# YOLO_Custom_Dataset **(It's my first  real github project！！)**

It's a python project which can trans `Open Images Dataset V6` to YOLO.   
And I have test it in my ubuntu 18.04 computer.   
Many thanks to `theAIGuysCode`, https://github.com/theAIGuysCode/YoloGenerateTrainingFile .   
My main code is from him.   


##How to use   
I watched the video in Youtube(https://www.youtube.com/watch?v=zJDUhGL26iU&list=PLKHYJbyeQ1a0oGzgRXy-QwAN1tSV4XZxg&index=5).    
It's very helpful for me about how to custom my own datasets from Open Images Dataset V6(https://storage.googleapis.com/openimages/web/index.html).   
But `theAIGuysCode` only teches how to creat `train.txt`, and I also need `test.txt`file in practice.   
So , I modified the `generate_train.py`.   


First of all, you need  copy your datasets(include image files and txt files ) to `./data/`.  
For example, my train datasets  and test datasets were placed in `./data/obj/train/` and `./data/obj/test/`.

If you want to generate `train.txt`, you just need run `python generate_train.py`.   
If you want to generate `test.txt`, you just need run `python generate_test.py`.   

