0- find other methods on https://paperswithcode.com/task/3d-face-reconstruction
1- Install MeshLab using Ubuntu Software. Required for opening 3d face file genereated by demo.py code in abc.obj formate.
2- install below packages
dlib                   19.18.0 
tensorflow             1.8.0 
scikit-image           0.16.2 
scikit-learn           0.19.1 
opencv-contrib-python  4.1.2.30 
opencv-python          4.1.1.26 

3- run the demo.py file
$python demo.py -i TestImages/ -o out/ --isDlib True
It will generate a .obj files in out/ directory
4- You can open the .obj file in MeshLab and see the 3d face image.

5- python demo.py -i veer/ -o veer_out/ --isPose True --isShow True
