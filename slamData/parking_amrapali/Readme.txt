Round - 1
    std::ofstream manualLabelsFile("manualLabels-1.txt");
    cv::VideoCapture cap1("../../../dataset/slamData/parking_amrapali/round-1-counter.avi");
    int frameCount = cap1.get(CV_CAP_PROP_FRAME_COUNT);

    // Manully set the labels range
    std::vector<cv::Vec2i> label1Ranges;
    label1Ranges.push_back(cv::Vec2i(2030,4525));

    std::vector<cv::Vec2i> label2Ranges;
    label2Ranges.push_back(cv::Vec2i(0,2030));
    label2Ranges.push_back(cv::Vec2i(4525,frameCount));

Round - 2
    std::ofstream manualLabelsFile("manualLabels-2.txt");
    cv::VideoCapture cap1("../../../dataset/slamData/parking_amrapali/round-2-counter.avi");
    int frameCount = cap1.get(CV_CAP_PROP_FRAME_COUNT);

    // Manully set the labels range
    std::vector<cv::Vec2i> label1Ranges;
    label1Ranges.push_back(cv::Vec2i(2080,4470));

    std::vector<cv::Vec2i> label2Ranges;
    label2Ranges.push_back(cv::Vec2i(0,2080));
    label2Ranges.push_back(cv::Vec2i(4470,frameCount));

Round - 3
    std::ofstream manualLabelsFile("manualLabels-3.txt");
    cv::VideoCapture cap1("../../../dataset/slamData/parking_amrapali/round-3-counter.avi");
    int frameCount = cap1.get(CV_CAP_PROP_FRAME_COUNT);

    // Manully set the labels range
    std::vector<cv::Vec2i> label1Ranges;
    label1Ranges.push_back(cv::Vec2i(2200,4900));

    std::vector<cv::Vec2i> label2Ranges;
    label2Ranges.push_back(cv::Vec2i(0,2200));
    label2Ranges.push_back(cv::Vec2i(4900,frameCount));


    std::ofstream manualLabelsFile("manualLabels-4.txt");
    cv::VideoCapture cap1("../../../dataset/slamData/parking_amrapali/round-4.mov");
    int frameCount = cap1.get(CV_CAP_PROP_FRAME_COUNT);

    // Manully set the labels range
    std::vector<cv::Vec2i> label1Ranges;
    label1Ranges.push_back(cv::Vec2i(2140,4780));

Round - 4
    std::vector<cv::Vec2i> label2Ranges;
    label2Ranges.push_back(cv::Vec2i(0,2140));
    label2Ranges.push_back(cv::Vec2i(4780,frameCount));
