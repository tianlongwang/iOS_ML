# Machine Learning for iOS 

## Tools and resources to create really smart iOS applications.

**Last Update: March 17, 2017.**

Curated list of resources for iOS developers in following topics: 

- Machine Learning, 
- Artificial Intelligence,
- Natural Language Processing (NLP), 
- Computer Vision, 
- General-Purpose GPU Computing (GPGPU), 
- Data Visualization,
- Bioinformatics

Most of the de-facto standard tools in domains listed above are written in iOS-unfriendly languages (Python/Java/R/Matlab) so find something appropriate for your iOS application may be a challenging task.
This list consists mainly of libraries written in Objective-C, Swift, C, C++, JavaScript and some other languages if they can be easily ported to iOS. Also links to some relevant web APIs, blog posts, videos and learning materials included.

**Pull-requests are welcome [here](https://github.com/alexsosn/iOS_ML)!**

## Where to learn about machine learning and related topics in general
* [Courserra course](https://www.coursera.org/learn/machine-learning/home/info) on machine learning from [Andrew Ng](https://twitter.com/AndrewYNg).
* [Machine learning playlist on Youtube](https://www.youtube.com/playlist?list=PLD0F06AA0D2E8FFBA).
* Free online interactive book ["Neural Networks and Deep Learning"](http://neuralnetworksanddeeplearning.com/).
* ["Natural Language Processing with Python"](http://www.nltk.org/book/) - free online book.
* [Heterogeneous Parallel Programming](https://www.coursera.org/course/hetero) course.
* Immersive Linear Algebra [interactive book](http://immersivemath.com/ila/index.html) by J. Ström, K. Åström, and T. Akenine-Möller.
* [Deep Learning for Perception](https://computing.ece.vt.edu/~f15ece6504/) by Virginia Tech, Electrical and Computer Engineering, Fall 2015: ECE 6504
* [Probabilistic Programming & Bayesian Methods for Hackers](http://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/) - An intro to Bayesian methods and probabilistic programming from a computation/understanding-first, mathematics-second point of view. 
* [CAP 5415 - Computer Vision](http://crcv.ucf.edu/courses/CAP5415/Fall2014/index.php) by UCF
* [CS224d: Deep Learning for Natural Language Processing](http://cs224d.stanford.edu/syllabus.html) by Stanford
* [Machine Learning: 2014-2015 Course materials](https://www.cs.ox.ac.uk/people/nando.defreitas/machinelearning/) by Oxford
* [Stanford CS class CS231n: Convolutional Neural Networks for Visual Recognition.](http://cs231n.stanford.edu/)
* [Deep Learning for Natural Language Processing \(without Magic\)](http://nlp.stanford.edu/courses/NAACL2013/)
* [Videos](http://videolectures.net/deeplearning2015_montreal/) from Deep Learning Summer School, Montreal 2015.
* [Deep Learning Summer School, Montreal 2016](http://videolectures.net/deeplearning2016_montreal/)
* ["Deep learning"](http://www.deeplearningbook.org/) - the book by Ian Goodfellow and Yoshua Bengio and Aaron Courville

## Web APIs

* [**IBM** Watson](http://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/) - Enable Cognitive Computing Features In Your App Using IBM Watson's Language, Vision, Speech and Data APIs.
	* [Introducing the (beta) IBM Watson iOS SDK](https://developer.ibm.com/swift/2015/12/18/introducing-the-new-watson-sdk-for-ios-beta/)
* [AlchemyAPI](http://www.alchemyapi.com/) - Semantic Text Analysis APIs Using Natural Language Processing. Now part of IBM Watson.
* [**Microsoft** Project Oxford](https://www.projectoxford.ai/)
* [**Google** Prediction engine](https://cloud.google.com/prediction/docs)
	* [Objective-C API](https://code.google.com/p/google-api-objectivec-client/wiki/Introduction)
* [Google Translate API](https://cloud.google.com/translate/docs)
* [Google Cloud Vision API](https://cloud.google.com/vision/)
* [**Amazon** Machine Learning](http://aws.amazon.com/documentation/machine-learning/) - Amazon ML is a cloud-based service for developers. It provides visualization tools to create machine learning models. Obtain predictions for application using APIs. 
	* [iOS developer guide](https://docs.aws.amazon.com/mobile/sdkforios/developerguide/getting-started-machine-learning.html).
	* [iOS SDK](https://github.com/aws/aws-sdk-ios)
* [**PredictionIO**](https://prediction.io/) - opensource machine learning server for developers and ML engineers. Built on Apache Spark, HBase and Spray.
	* [Swift SDK](https://github.com/minhtule/PredictionIO-Swift-SDK)
	* [Tapster iOS Demo](https://github.com/minhtule/Tapster-iOS-Demo) - This demo demonstrates how to use the PredictionIO Swift SDK to integrate an iOS app with a PredictionIO engine to make your mobile app more interesting.
	* [Tutorial](https://github.com/minhtule/Tapster-iOS-Demo/blob/master/TUTORIAL.md) on using Swift with PredictionIO.
* [**Wit.AI**](https://wit.ai/) - NLP API
* [**Yandex** SpeechKit](https://tech.yandex.com/speechkit/mobilesdk/) Text-to-speech and speech-to-text for Russian language. iOS SDK available.
* [**Abbyy** OCR SDK](http://www.abbyy.com/mobile-ocr/iphone-ocr/)
* [**Clarifai**](http://www.clarifai.com/#) - deep learning web api for image captioning. [iOS starter project](https://github.com/Clarifai/clarifai-ios-starter)
* [**MetaMind**](https://www.metamind.io/) - deep learning web api for image captioning.
* [Api.AI](https://api.ai/) - Build intelligent speech interfaces
for apps, devices, and web
* [**CloudSight.ai**](https://cloudsight.ai/) - deep learning web API for fine grained object detection or whole screen description, including natural language object captions. [Objective-C](https://github.com/cloudsight/cloudsight-objc) API client is available.


## General-Purpose Machine Learning Libraries

* [FANN](https://cocoapods.org/pods/FANN) - Fast Artifical Neural Network library; an implementation of neural networks.
* [lbimproved](https://github.com/lemire/lbimproved) - DTW + kNN in C
* **Shark** - provides libraries for the design of adaptive systems, including methods for linear and nonlinear optimization (e.g., evolutionary and gradient-based algorithms), kernel-based algorithms and neural networks, and other machine learning techniques. [CocoaPods](https://cocoapods.org/pods/Shark-SDK). [Official site](http://image.diku.dk/shark/sphinx_pages/build/html/index.html)
* [YCML](http://yconst.com/software/ycml/) - A Machine Learning framework for Objective-C and Swift (OS X / iOS). 
The following algorithms are currently available: Gradient Descent Backpropagation, Resilient Backpropagation (RProp), Extreme Learning Machines (ELM), Forward Selection using Orthogonal Least Squares (for RBF Net), also with the PRESS statistic, Binary Restricted Boltzmann Machines (CD & PCD, Untested!). YCML also contains some optimization algorithms as support for deriving predictive models, although they can be used for any kind of problem: Gradient Descent (Single-Objective, Unconstrained), RProp Gradient Descent (Single-Objective, Unconstrained), NSGA-II (Multi-Objective, Constrained).
	* [Github](https://github.com/yconst/ycml/). 
* [Swix](https://github.com/scottsievert/swix) - Swift implementation of NumPy.
* [Brain](https://github.com/harthur/brain) - Neural networks in JavaScript. Unmaintained.
* [April-ANN](https://github.com/pakozm/april-ann) - APRIL-ANN toolkit (A Pattern Recognizer In Lua with ANNs). This toolkit incorporates ANN algorithms (as dropout, stacked denoising auto-encoders, convolutional NNs), with other pattern recognition methods as HMMs among others. Additionally, in experimental stage, it is possible to perform automatic differentiation, for advanced ML research. Potentially can be ported for iOS. 
	* [Official Site](http://pakozm.github.com/april-ann/). 
* [Recommender](https://github.com/GHamrouni/Recommender) - A C library for product recommendations/suggestions using collaborative filtering (CF).
* [SNNeuralNet](https://github.com/devongovett/SNNeuralNet) - A neural network library for Objective-C based on brain.js, for iOS and Mac OS X.
* [MLPNeuralNet](https://github.com/nikolaypavlov/MLPNeuralNet) - Fast multilayer perceptron neural network library for iOS and Mac OS X. MLPNeuralNet predicts new examples by trained neural network. It is built on top of the Apple's Accelerate Framework, using vectorized operations and hardware acceleration if available.
* [MAChineLearning](https://github.com/gianlucabertani/MAChineLearning) - An Objective-C multilayer perceptron library, with full support for training through backpropagation. Implemented using vDSP and vecLib, it's 20 times faster than its Java equivalent. Includes sample code for use from Swift.
* [Swift-AI](https://github.com/collinhundley/Swift-AI) - 3-layer NN.
* [EERegression](https://github.com/erkekin/EERegression/) -  General purpose multivaritate and quadratic Regression library for Swift 2.1 
* [SwiftSimpleNeuralNetwork](https://github.com/davecom/SwiftSimpleNeuralNetwork) - Feed forward and back propagation.
* [STEM](https://github.com/abeschneider/stem) - Swift Tensor Engine for Machine-learning
	* [Documentation](http://stem.readthedocs.io/en/latest/) 
* [multilinear-math](https://github.com/vincentherrmann/multilinear-math) - Swift library for tensor operations, machine learning and artificial intelligence
* [MLKit](https://github.com/Somnibyte/MLKit) - regressions, cross-validation, data splitting.
* [dlib](http://dlib.net/) is a C++ framework which contains 30+ machine learning algorithms and different useful additions. It's relatively easy to port it to iOS: you just need to get rid of GUI and http-related source files.
* [Mendel](https://github.com/saniul/Mendel) - Genetic algorithms in Swift.

* **Kalvar Lin's libraries**
	* [ios-BPN-NeuralNetwork](https://github.com/Kalvar/ios-BPN-NeuralNetwork) - 3-layer neural network + back propagation.
	* [ios-Multi-Perceptron-NeuralNetwork](https://github.com/Kalvar/ios-Multi-Perceptron-NeuralNetwork) - Multi-perceptron neural network based on back propagation NN.
	* [ios-KRDelta](https://github.com/Kalvar/ios-KRDelta) - [Delta Learning method](https://en.wikipedia.org/wiki/Delta_rule)
	* [ios-KRHebbian-Algorithm](https://github.com/Kalvar/ios-KRHebbian-Algorithm) - [Hebbian Theory](https://en.wikipedia.org/wiki/Hebbian_theory)
	* [ios-KRKmeans-Algorithm](https://github.com/Kalvar/ios-KRKmeans-Algorithm) - [K-Means](https://en.wikipedia.org/wiki/K-means_clustering) clustering method.
	* [ios-KRFuzzyCMeans-Algorithm](https://github.com/Kalvar/ios-KRFuzzyCMeans-Algorithm) - [Fuzzy C-Means](https://en.wikipedia.org/wiki/Fuzzy_clustering), the fuzzy clustering algorithm.
	* [ios-KRGreyTheory](https://github.com/Kalvar/ios-KRGreyTheory) - [Grey Theory](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.678.3477&rep=rep1&type=pdf) / [Grey system theory-based models in time series prediction](http://www.mecha.ee.boun.edu.tr/Prof.%20Dr.%20Okyay%20Kaynak%20Publications/c%20Journal%20Papers(appearing%20in%20SCI%20or%20SCIE%20or%20CompuMath)/62.pdf)
	* [ios-KRSVM](https://github.com/Kalvar/ios-KRSVM) - Support Vector Machine and SMO.
	* [ios-KRKNN](https://github.com/Kalvar/ios-KRKNN) - kNN implementation.
	* [ios-KRRBFNN](https://github.com/Kalvar/ios-KRRBFNN) - Radial basis function neural network and OLS.
	* [ios-KRPerceptron](https://github.com/Kalvar/ios-KRPerceptron) - Perceptron method.
	* [ios-ML-Recommendation-System](https://github.com/Kalvar/ios-ML-Recommendation-System) - demo of a book recommendation system, built using ios-BPN-NeuralNetwork. 

### Deep Learning
* [Torch-iOS](https://github.com/clementfarabet/torch-ios) - [Torch](http://torch.ch/) port for iOS. Torch is a scientific computing framework with wide support for machine learning algorithms. One of the most popular deep learning frameworks.
* [Caffe](http://caffe.berkeleyvision.org) - A deep learning framework developed with cleanliness, readability, and speed in mind.
[GitHub](https://github.com/BVLC/caffe). [BSD]
	* [iOS port](https://github.com/aleph7/caffe)
	* C++ examples: [Classifying ImageNet](http://caffe.berkeleyvision.org/gathered/examples/cpp_classification.html), [Extracting Features](http://caffe.berkeleyvision.org/gathered/examples/feature_extraction.html)
	* [Caffe iOS sample](https://github.com/noradaiko/caffe-ios-sample)
* [Caffe2](https://github.com/caffe2/caffe2) - a cross-platform framework made with expression, speed, and modularity in mind.
* [Deep Belief SDK](https://github.com/jetpacapp/DeepBeliefSDK) -  The SDK for Jetpac's iOS Deep Belief image recognition framework
* [Convnet.js](http://cs.stanford.edu/people/karpathy/convnetjs/) - ConvNetJS is a Javascript library for training Deep Learning models by [Andrej Karpathy](https://twitter.com/karpathy). [GitHub](https://github.com/karpathy/convnetjs)
	* [ConvNetSwift](https://github.com/alexsosn/ConvNetSwift) - Swift port [work in progress].
* [MXNet](http://mxnet.readthedocs.org/en/latest/) - MXNet is a deep learning framework designed for both efficiency and flexibility.
	* [Deploying mxnet to smartphone](https://github.com/dmlc/mxnet/tree/master/amalgamation)
* [BNNS](https://developer.apple.com/reference/accelerate/1912851-bnns) - Apple Basic neural network subroutines (BNNS) is a collection of functions that you use to implement and run neural networks, using previously obtained training data.
	* [BNNS usage examples](https://github.com/shu223/iOS-10-Sampler) in iOS 10 sampler.
* [TensorFlow](http://www.tensorflow.org/) - an open source software library for numerical computation using data flow graphs. Nodes in the graph represent mathematical operations, while the graph edges represent the multidimensional data arrays (tensors) communicated between them. The flexible architecture allows you to deploy computation to one or more CPUs or GPUs in a desktop, server, or mobile device with a single API.
	* [iOS examples](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/contrib/ios_examples)
* [DeepLearningKit](http://deeplearningkit.org/) - Open Source Deep Learning Framework from Memkite for Apple's tvOS, iOS and OS X.
* [tiny-dnn](https://github.com/tiny-dnn/tiny-dnn) - header only, dependency-free deep learning framework in C++11
	* [iOS example](https://github.com/tiny-dnn/tiny-dnn/tree/d4fff53fa0d01f59eb162de2ec32c652a1f6f467/examples/ios) 
* [NNPACK](https://github.com/Maratyszcza/NNPACK) - Acceleration package for neural networks on multi-core CPUs. Prisma [uses](http://prisma-ai.com/libraries.html) this library in the mobile app.
* [BrainCore](https://github.com/aleph7/BrainCore) - simple but fast neural network framework written in Swift. It uses Metal framework to be as fast as possible. ReLU, LSTM, L2 ...
* [Espresso](https://github.com/codinfox/espresso) - A minimal high performance parallel neural network framework running on iOS

## Game AI
* [Introduction to AI Programming for Games](http://www.raywenderlich.com/24824/introduction-to-ai-programming-for-games)
* [dlib](http://dlib.net/) is a library which has many useful tools including machine learning.
* [MicroPather](http://www.grinninglizard.com/MicroPather/) is a path finder and A* solver (astar or a-star) written in platform independent C++ that can be easily integrated into existing code.
* Here is a [list](http://www.ogre3d.org/tikiwiki/List+Of+Libraries#Artificial_intelligence) of some AI libraries suggested on OGRE3D website. Seems they are mostly written in C++.
* [GameplayKit Programming Guide](https://developer.apple.com/library/content/documentation/General/Conceptual/GameplayKit_Guide/)


## Natural Language Processing
* [Parsimmon](https://github.com/ayanonagon/Parsimmon)
* [NSLinguisticTagger](http://nshipster.com/nslinguistictagger/)
* [Word2Vec](https://code.google.com/p/word2vec/) - Original C implementation of Word2Vec Deep Learning algorithm. Works on iPhone like a charm.
* [Twitter text](https://github.com/twitter/twitter-text-objc) - 
An Objective-C implementation of Twitter's text processing library. The library includes methods for extracting user names, mentions headers, hashtags, and more – all the tweet specific language syntax you could ever want.

## Speech Recognition (TTS) and Generation (STT)
* [TLSphinx](https://github.com/tryolabs/TLSphinx), [Tutorial](http://blog.tryolabs.com/2015/06/15/tlsphinx-automatic-speech-recognition-asr-in-swift/)
* [MVSpeechSynthesizer](https://github.com/vimalmurugan89/MVSpeechSynthesizer)
* [OpenEars™: free speech recognition and speech synthesis for the iPhone](http://www.politepix.com/openears/) - OpenEars™ makes it simple for you to add offline speech recognition and synthesized speech/TTS to your iPhone app quickly and easily. It lets everyone get the great results of using advanced speech UI concepts like statistical language models and finite state grammars in their app, but with no more effort than creating an NSArray or NSDictionary. 
	* [Tutorial (Russian)](http://habrahabr.ru/post/237589/)
* [Kaldi-iOS framework](http://keenresearch.com/) - on-device speech recognition using deep learning.
	* [Proof of concept app](https://github.com/keenresearch/kaldi-ios-poc)


## Computer Vision
* [**Vuforia** Framework](https://developer.vuforia.com/downloads/sdk)
	* [Object detection with Vuforia tutorial.](http://habrahabr.ru/company/dataart/blog/256385/) \(Russian\)

* **[OpenCV](http://opencv.org)** – Open Source Computer Vision Library. [BSD]
	* [OpenCV crash course](http://www.pyimagesearch.com/free-opencv-crash-course/
) 
	* [OpenCVSwiftStitch](https://github.com/foundry/OpenCVSwiftStitch)
	* [Tutorial: using and building openCV on iOS devices](http://maniacdev.com/2011/07/tutorial-using-and-building-opencv-open-computer-vision-on-ios-devices)

* [trackingjs](http://trackingjs.com/) – Object tracking in JS
* [OpenFace](https://github.com/TadasBaltrusaitis/OpenFace) – a state-of-the art open source tool intended for facial landmark detection, head pose estimation, facial action unit recognition, and eye-gaze estimation.
	* [iOS port](https://github.com/FaceAR/OpenFaceIOS)
* [ccv](http://libccv.org) - C-based/Cached/Core Computer Vision Library, A Modern Computer Vision Library
	* [iOS demo app](https://github.com/liuliu/klaus)
* [OpenFace](https://github.com/TadasBaltrusaitis/OpenFace) – a state-of-the art open source tool intended for facial landmark detection, head pose estimation, facial action unit recognition, and eye-gaze estimation.
	* [iOS demo](https://github.com/FaceAR/OpenFaceIOS)

### Text Recognition (OCR)
* **Tesseract**
	* [Install and Use Tesseract on iOS](http://lois.di-qual.net/blog/install-and-use-tesseract-on-ios-with-tesseract-ios/)
	* [tesseract-ios-lib](https://github.com/ldiqual/tesseract-ios-lib)
	* [tesseract-ios](https://github.com/ldiqual/tesseract-ios)
	* [Tesseract-OCR-iOS](https://github.com/gali8/Tesseract-OCR-iOS)
	* [OCR-iOS-Example](https://github.com/robmathews/OCR-iOS-Example)
* [ocrad.js](https://github.com/antimatter15/ocrad.js) - JS OCR

## General Math
* [Surge](https://github.com/mattt/Surge) from Mattt
* [Upsurge](https://github.com/aleph7/Upsurge) - tensors, matrices, Accelerate support
* [YCMatrix](https://github.com/yconst/YCMatrix) - A flexible Matrix library for Objective-C and Swift (OS X / iOS)
* [Eigen](http://eigen.tuxfamily.org/) - A high-level C++ library of template headers for linear algebra, matrix and vector operations, numerical solvers and related algorithms. [MPL2]
* [SigmaSwiftStatistics](https://github.com/evgenyneu/SigmaSwiftStatistics) - A collection of functions for statistical calculation written in Swift.
* [RandKit](https://github.com/aidangomez/RandKit) - Swift framework for random numbers & distributions.

## Optimization

* [fmincg-c](https://github.com/gautambhatrcb/fmincg-c) - Conjugate gradient implementation in C
* [libLBFGS](https://github.com/chokkan/liblbfgs) - a C library of Limited-memory Broyden-Fletcher-Goldfarb-Shanno (L-BFGS)


## Feature extraction
* [IntuneFeatures](https://github.com/venturemedia/intune-features) framework contains code to generate features from audio files and feature labels from the respective MIDI files.
* [matchbox](https://github.com/hfink/matchbox) - Mel-Frequency-Cepstral-Coefficients and Dynamic-Time-Warping for iOS/OSX
* [LibXtract](https://github.com/jamiebullock/LibXtract) is a simple, portable, lightweight library of audio feature extraction functions.


## GPGPU

### Articles
* [OpenCL for iOS](https://github.com/linusyang/opencl-test-ios) - just a test.
* Exploring GPGPU on iOS. 
	* [Article](http://ciechanowski.me/blog/2014/01/05/exploring_gpgpu_on_ios/) 
	* [Code](https://github.com/Ciechan/Exploring-GPGPU-on-iOS
)

* GPU-accelerated video processing for Mac and iOS. [Article](http://www.sunsetlakesoftware.com/2010/10/22/gpu-accelerated-video-processing-mac-and-ios0).

* [Concurrency and OpenGL ES](https://developer.apple.com/library/ios/documentation/3ddrawing/conceptual/opengles_programmingguide/ConcurrencyandOpenGLES/ConcurrencyandOpenGLES.html) - Apple programming guide.

* [OpenCV on iOS GPU usage](http://stackoverflow.com/questions/10704916/opencv-on-ios-gpu-usage) - SO discussion.

#### Metal
* Simon's Gladman \(aka flexmonkey\) [blog](http://flexmonkey.blogspot.com/)
	* [Talk on iOS GPU programming](https://realm.io/news/altconf-simon-gladman-ios-gpu-programming-with-swift-metal/) with Swift and Metal at Realm Altconf.
	* [The Supercomputer In Your Pocket:
Metal & Swift](https://realm.io/news/swift-summit-simon-gladman-metal/) - a video from the Swift Summit Conference 2015
	* https://github.com/FlexMonkey/MetalReactionDiffusion
	* https://github.com/FlexMonkey/ParticleLab
* [Memkite blog](http://memkite.com/) - startup intended to create deep learning library for iOS.
	* [Swift and Metal example for General Purpose GPU Processing on Apple TVOS 9.0](https://github.com/memkite/MetalForTVOS)
	* [Data Parallel Processing with Swift and Metal on GPU for iOS8](https://github.com/memkite/SwiftMetalGPUParallelProcessing)
	* [Example of Sharing Memory between GPU and CPU with Swift and Metal for iOS8](http://memkite.com/blog/2014/12/30/example-of-sharing-memory-between-gpu-and-cpu-with-swift-and-metal-for-ios8/)
* [Metal by Example blog](http://metalbyexample.com/)
* [objc-io article on Metal](https://www.objc.io/issues/18-games/metal/)

### GPU-accelerated libraries
* [GPUImage](https://github.com/BradLarson/GPUImage) is a GPU-accelerated image processing library.

## Data Visualization
* [Charts](https://github.com/danielgindi/Charts) - The Swift port of the MPAndroidChart.
* [iOS-Charts](https://github.com/danielgindi/ios-charts)
* [Core Plot](https://github.com/core-plot/core-plot)
* [Awesome iOS charts](https://github.com/sxyx2008/awesome-ios-chart)
* [JTChartView](https://github.com/kubatru/JTChartView)
* [VTK](http://www.vtk.org/gallery/)
	* [VTK in action](http://www.vtk.org/vtk-in-action/)

## Bioinformatics
* [BioJS](http://biojs.net/) - a set of tools for bioinformatics in the browser. BioJS builds a infrastructure, guidelines and tools to avoid the reinvention of the wheel in life sciences. Community builds modules than can be reused by anyone.
* [BioCocoa](http://www.bioinformatics.org/biococoa/wiki/pmwiki.php) - BioCocoa is an open source OpenStep (GNUstep/Cocoa) framework for bioinformatics written in Objective-C. [Dead project].
* [iBio](https://github.com/Lizhen0909/iBio) - A Bioinformatics App for iPhone.


## Big Data
* [HDF5Kit](https://github.com/aleph7/HDF5Kit) - This is a Swift wrapper for the HDF5 file format. HDF5 is used in the scientific comunity for managing large volumes of data. The objective is to make it easy to read and write HDF5 files from Swift, including playgrounds.

# Opensource Applications
* [DeepDreamer](https://github.com/johndpope/deepdreamer) - Deep Dream application
* [DeepDreamApp](https://github.com/johndpope/DeepDreamApp) - Deep Dream Cordova app.
* [Swift implementation of Joel Grus's "Data Science from Scratch"](https://github.com/graceavery/LearningMachineLearning)
* [Texture Networks](https://github.com/DmitryUlyanov/texture_nets), Lua implementation
* [Feedforward style transfer](https://github.com/jcjohnson/fast-neural-style), Lua implementation
* [TensorFlow implementation of Neural Style](https://github.com/cysmith/neural-style-tf)
* [Corrosion detection app](https://github.com/jmolayem/corrosionapp)
* [Classical ELIZA chatbot in Swift](https://gist.github.com/hollance/be70d0d7952066cb3160d36f33e5636f)
* [InfiniteMonkeys](https://github.com/craigomac/InfiniteMonkeys) - A Keras-trained RNN to emulate the works of a famous poet, powered by BrainCore
* [SwiftOCR](https://github.com/garnele007/SwiftOCR)
* [WhatsThis](https://github.com/pppoe/WhatsThis-iOS)
* [enVision](https://github.com/IDLabs-Gate/enVision)
* [ios_camera_object_detection](https://github.com/yjmade/ios_camera_object_detection) - Realtime mobile visualize based Object Detection based on TensorFlow and YOLO model
* [TensorFlow MNIST iOS demo](https://github.com/mattrajca/MNIST) - Getting Started with Deep MNIST and TensorFlow on iOS


# Other Lists
* [Awesome Machine Learning](https://github.com/josephmisiti/awesome-machine-learning)
* [Machine Learning Courses](https://github.com/prakhar1989/awesome-courses#machine-learning)
* [Awesome Data Science](https://github.com/okulbilisim/awesome-datascience)
* [Awesome Computer Vision](https://github.com/jbhuang0604/awesome-computer-vision)
* [Speech and language processing](https://github.com/edobashira/speech-language-processing)
* [The Rise of Chat Bots:](https://stanfy.com/blog/the-rise-of-chat-bots-useful-links-articles-libraries-and-platforms/)  Useful Links, Articles, Libraries and Platforms by Pavlo Bashmakov.

# Articles, Blog posts, Papers

## General

* [Intelligence in Mobile Applications](https://medium.com/@sadmansamee/intelligence-in-mobile-applications-ca3be3c0e773#.lgk2gt6ik)
* [An exclusive inside look at how artificial intelligence and machine learning work at Apple](https://backchannel.com/an-exclusive-look-at-how-ai-and-machine-learning-work-at-apple-8dbfb131932b)


## Deep Learning

* [Use TensorFlow and BNNS to Add Machine Learning to your Mac or iOS App](https://www.bignerdranch.com/blog/use-tensorflow-and-bnns-to-add-machine-learning-to-your-mac-or-ios-app/)
* [Machine Learning for iOS](https://www.invasivecode.com/weblog/machine-learning-swift-ios/)
* [Convolutional Neural Networks in iOS 10 and macOS](https://www.invasivecode.com/weblog/convolutional-neural-networks-ios-10-macos-sierra/)
* [The “hello world” of neural networks](http://matthijshollemans.com/2016/08/24/neural-network-hello-world/) - Swift and BNNS
* [Convolutional neural networks on the iPhone with VGGNet](http://matthijshollemans.com/2016/08/30/vggnet-convolutional-neural-network-iphone/)
* [How to Quantize Neural Networks with TensorFlow](https://petewarden.com/2016/05/03/how-to-quantize-neural-networks-with-tensorflow/)
* [Presentation on squeezing DNNs for mobile](https://www.slideshare.net/mobile/anirudhkoul/squeezing-deep-learning-into-mobile-phones)

## Information security and ML

* [(sp)iPhone: Decoding Vibrations From Nearby Keyboards
Using Mobile Phone Accelerometers](http://www.cc.gatech.edu/~traynor/papers/traynor-ccs11.pdf)


# People to follow in iOS machine learning and related topics
\(In alphabet order\).

* **Alejandro** - BrainCore and Caffe for iOS author. [Blog](http://a-coding.com). {% include icon-twitter.html username="aleph7" %}
* **Simon Gladman** - Swift and Metal enthusiast and blogger. [Blog](http://flexmonkey.blogspot.com/). {% include icon-twitter.html username="flexmonkey" %}
* **Matthijs Hollemans** - Swift, Metal and neural networks. [Blog](http://matthijshollemans.com/). {% include icon-twitter.html username="mhollemans" %}
* **Andrej Karpathy** - Research Scientist at OpenAI. ConvNetJS author. [Blog](http://karpathy.github.io/). {% include icon-twitter.html username="karpathy" %}
* **Kalvar Lin** - Implemented a set of small machine learning libraries for iOS and Ruby. {% include icon-twitter.html username="ilovekalvar" %}
* **Memkite team** - Memkite is a Deep Learning framework for iOS that can be used to support Artificial Intelligence (AI) in apps. {% include icon-twitter.html username="memkite" %}
	* **Torbjørn Morland** {% include icon-twitter.html username="torbmorland" %}
	* **Amund Tveit** {% include icon-twitter.html username="atveit" %}
* **Geppy Parziale** - You can find several of his ML & iOS articles at www.invasivecode.com. {% include icon-twitter.html username="geppyp" %}

