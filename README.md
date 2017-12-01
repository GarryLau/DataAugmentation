# DataAugmentation
Caffe Image Data Augmentation
此数据增强是针对利用原始图片进行训练（image_data_layer.cpp）的方式进行的。
实际应用时从https://github.com/BVLC/caffe 下载官方caffe然后将caffe.proto、data_transformer.cpp、data_transformer.hpp替换掉原版caffe即可。
train_val.prototxt中transform_param的配置参考transform_param.txt，其中备注随机的参数推荐只对train做，不要对test\val数据做。
