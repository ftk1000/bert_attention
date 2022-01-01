# [Boris Burkov](http://burkov.net)

* [2021.12.25: How DeepMind AlphaFold2 works?](http://burkov.net/2021-12-25-1/)
* [2021.08.03:  Kernel methods and Reproducing Kernel Hilbert Space (RKHS)](http://burkov.net/2021-08-03-1/) - check out the superb list of references at the end! 
  * [YT: 2012: CalTech:  Lecture 15 - Kernel Methods](https://www.youtube.com/watch?v=XUj5JbQihlU)
    * Kernel Methods - Extending SVM to infinite-dimensional spaces using the kernel trick, and to non-separable data using soft margins. Lecture 15 of 18 of Caltech's Machine Learning Course - CS 156 by Professor Yaser Abu-Mostafa. View course materials in iTunes U Course App - https://itunes.apple.com/us/course/ma... and on the course website - http://work.caltech.edu/telecourse.html 
  * [2021: Arthur Gretton: slides: Reproducing kernel Hilbert spaces in Machine Learning](https://www.gatsby.ucl.ac.uk/~gretton/coursefiles/Slides4A.pdf)
  * [YT:2021: Arthur Gretton talk](https://www.youtube.com/watch?v=alrKls6BORc)
    * Kernel methods push data into higher dimention feature space to solve problem: see slide 10 ~ 12:00 min
    * Smooth vs Rough features: Kernel methods can control smoothness and avoid overfitting/underfitting. Slide 11
  
# Kernel Mehods
* Vec Sp has an inner product f: VxV->R if f is 1) linear, 2) symmetric f(v,w)=f(w,v), 3) positive definite: f(v,v) >= 0 and f(v,v)=0 iff v=0.
* Hilbert space H is a VecSp with an Inner Product (I.P.) that induces a norm, and H is a complete metric space wrt norm induced by the I.P.
* Kernel (slide 13, 15:25 sec): k:XxX->R is a kernel if there is R-Hilber Space H and a map m:X->H s.t. k(x,x') = <m(x), m(x')>.
  * Ie, kernel is a dot product of features m(x), m(x') 
  * Almost no cond on X (text, image, etc).
  * A single kernel k may correspond to several features 
 
 
