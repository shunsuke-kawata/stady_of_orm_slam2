## 関数実行の順序

#### 呼び出し順
1. ```ros::Subscriber sub = nodeHandler.subscribe("/camera/image_raw", 1, &ImageGrabber::GrabImage,&igb);``` (ros_mono.cc)

1. ```mpSLAM->TrackMonocular(cv_ptr->image,cv_ptr->header.stamp.toSec());``` (ros_mono.cc)

1. ```cv::Mat Tcw = mpTracker->GrabImageMonocular(im,timestamp);``` (System.cc)