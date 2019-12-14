Explanation of metric:

intersection = which pixels appear both in predict and groundtruth

union =  all the pixels, appear in predict and groundtruth

IoU(intersection over union) = intersection/union

precision = tp/(tp+fp+fn)

tp: predict obj==groundtruth obj > threshold (0.5)

fp: predict obj no match groundtruth obj

fn: groundtruth obj no match predict obj

Avg precision - simple sum(precision)/count(precision)

Instance segmentation - find area of nuclea and detect area for each particular object

Semantic segmentation - find area which contain nuclea and returns this area as one object


