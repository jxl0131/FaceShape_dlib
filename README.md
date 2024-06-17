# UPDATE
主要改动：
- 做了一些修改以直接输出脸型估计结果
- 排除了一个index越界的bug
测试结果：
脸型分类标准和主流的五分类不一致，且结果不太准确，但是可以作为一个参考。

* FaceShape *

The project determines the face shape. (oval/rectangular/oblong/square/round/diamond/triangle )

Face shape helps you to decide hairstyle scientifically.

* Procedure to run this program: *
1. locate the haarcascade file, dlib .dat file in the repository.
2. place the image file( face photo) in the same repository.
3. run the program


![original and final image](https://github.com/rajendra7406/FaceShape/blob/master/results.png)

This face shape is square 

1. Line1 shows forehead length
2. Line2 shows face width
3. Line3 shows jawline length
4. Line4 shows face length

Based on the proportions of these lines face shape is calculated.
Even the angle of jaw is calculated. 

The accuracy of the result is highly subjective.