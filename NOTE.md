py-faster-rcnn中的caffe-fast-rcnn以"33f2445b47fddd260ac59901c0920f2bb671d579"为基准，在此基础上新增下面的文件
py-faster-rcnn\caffe-fast-rcnn\include\caffe\fast_rcnn_layers.hpp
py-faster-rcnn\caffe-fast-rcnn\include\caffe\layer.hpp
py-faster-rcnn\caffe-fast-rcnn\include\caffe\layers\dropout_layer.hpp
py-faster-rcnn\caffe-fast-rcnn\include\caffe\layers\python_layer.hpp
py-faster-rcnn\caffe-fast-rcnn\LICENSE
py-faster-rcnn\caffe-fast-rcnn\python\caffe\__init__.py
py-faster-rcnn\caffe-fast-rcnn\python\caffe\_caffe.cpp
py-faster-rcnn\caffe-fast-rcnn\src\caffe\layers\dropout_layer.cpp
py-faster-rcnn\caffe-fast-rcnn\src\caffe\layers\dropout_layer.cu
py-faster-rcnn\caffe-fast-rcnn\src\caffe\layers\roi_pooling_layer.cpp
py-faster-rcnn\caffe-fast-rcnn\src\caffe\layers\roi_pooling_layer.cu
py-faster-rcnn\caffe-fast-rcnn\src\caffe\layers\smooth_L1_loss_layer.cpp
py-faster-rcnn\caffe-fast-rcnn\src\caffe\layers\smooth_L1_loss_layer.cu
py-faster-rcnn\caffe-fast-rcnn\src\caffe\proto\caffe.proto
py-faster-rcnn\caffe-fast-rcnn\src\caffe\test\test_roi_pooling_layer.cpp
py-faster-rcnn\caffe-fast-rcnn\src\caffe\test\test_smooth_L1_loss_layer.cpp

git clean -f && git reset --hard "33f2445b47fddd260ac59901c0920f2bb671d579" 