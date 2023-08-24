download casia dataset first


run test me_face.py


python test_face.py -method apc -fm arcface -d lfw -a 0.7 -data_folder data -l 4 -crop

can change  -fm arcface====>-fm facenet
                    -a=(0,0.3,0.7,1.0)
                    -crop====>-mask  /  -sunglass  /  blank