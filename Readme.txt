训练命令

具体参考：
https://learncodebygaming.com/blog/training-a-cascade-classifier
https://www.youtube.com/watch?v=XrCAvs9AePM
https://docs.opencv.org/4.2.0/dc/d88/tutorial_traincascade.html


示例：
opencv_traincascade -data /content/weiqi-haar/black/classifier -precalcValBufSize 5000 -precalcIdxBufSize 4000  -vec /content/weiqi-haar/black/pos_samples.vec -bg neg.lst -numPos 31 -numNeg 200 -numStages 25 -minHitRate 0.999 -mode ALL 