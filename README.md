# Multi-style-transfer-using-VGG19

 
In our project, we delve into the realm of digital art by exploring the concept of multi-style art transfer using the VGG19 model. This model, known for its effectiveness in image recognition, is repurposed to understand the style and content of different images. By analyzing these aspects, we can merge multiple artistic styles onto a single image, creating a new artwork that blends the characteristics of each style. Our project focuses on enhancing the efficiency and quality of this process. By optimizing the model and algorithms, we aim to make the multi-style art transfer more accessible and user-friendly. This project opens up new avenues for digital artists and enthusiasts to explore diverse artistic styles and create captivating artworks with ease.
INTRODUCTION
Artistic style transfer is a fascinating area of research in computer vision and deep learning, aiming to blend the style of one image with the content of another. Traditional methods have shown remarkable results, but recent advancements in neural networks have revolutionized this field. One such approach is the use of convolutional neural networks (CNNs) like VGG19, which excel at capturing complex features in images.
While existing research has focused on transferring the style of a single image, this project explores the realm of multi-style art transfer. The goal is to combine the styles of multiple reference images into a single output image, thereby offering more creative possibilities for artists and designers.
In this paper, we present a detailed analysis and implementation of multi-style art transfer using the VGG19 model. We explore the challenges and considerations involved in this task and propose novel techniques to address them. Additionally, we evaluate the performance of our approach using standard metrics and compare it with existing methods.
Our future work includes expanding this approach to support more than two styles and incorporating mechanisms to control the blending of styles, providing artists with greater flexibility and control over the artistic rendering process.
II.LITERATURE SURVEY
A. Fast Video Multi-Style Transfer
The paper proposes a novel approach to video style transfer that addresses issues such as flickering effects and limited applicability to short video clips found in existing algorithms. This paper discusses the use of Multi instance normalisation block and a convLSTM module. The proposed method is demonstrated to produce visually pleasing and temporally consistent stylized video results across various styles. It surpasses single-style models and post-processing techniques designed to reduce flickering effects.   In summary, the paper presents an innovative video style transfer approach that combines multi-instance normalization and ConvLSTM to achieve high-quality and consistent stylized video results across diverse styles, effectively overcoming limitations of existing methods.


B. Multi Style Generative Network for Real-time Transfer:
The MSG-Net model introduces the CoMatch Layer for improved style transfer, achieving real-time performance and superior image quality. However, limitations include unspecified computational requirements, limited evaluation of CoMatch Layer effectiveness across diverse styles, and the need for validation of claimed image quality superiority. Additionally, while compatible with various techniques, seamless integration and optimal performance across scenarios require further investigation.


II. DATASET
VGG19 model is pre-trained on Imagenet dataset. The ImageNet dataset consists of millions of labeled images across thousands of categories. The images in the ImageNet dataset cover a wide range of categories, including animals, plants, objects, and scenes. Each image is annotated with a single label that represents the category to which it belongs. The dataset has been instrumental in advancing the field of computer vision, particularly in the development of deep learning models for image recognition tasks.

 

III. MODEL USED
Models used in different types of transformations are different from Convolutional Neural Networks (CNN) and are often based on models such as VGG19. VGG19, proposed by Simonyan and Zisserman in 2014, has a 19-layer deep architecture consisting of 16 layers based on a layer-by-layer scheme (ReLU) processing interface with a maximum pooling layer for spatial subsampling. Its integrated structure and small 3x3 convolutional filter make it ideal for special operations. The model captures the content and representation of the input image by extracting features from various layers of the VGG19 network. These features are then used to calculate content and style drop, which are optimized to create a stylized image that combines the content of the image content with the structure of various image styles. Like VGG19 in the adaptive transformation algorithm, it allows features to benefit from different images using adaptive learning. Additionally, various aspects of the CNN architecture allow the model to adapt to a variety of performance and image content, providing users with a variety of creative possibilities in the process of creating digital images. Previously learned CNN, such as VGG19, which is the basis of extraction and transformation operations, is used for many types of transformations and makes it easy to combine stylized images to seamlessly provide original content with various artworks.

IV.MODEL ARCHITECTURE

VGG19 architecture is very simple and deep structured. It consists of 19 layers, out of which 16 are convolutional layers. Each convolutional layer is followed by a ReLU(Rectified linear unit) activation function. This convolutional layer is distributed with input max-pooling layers for spatial subsampling and feature reduction.
VGG19 in particular uses a small 3x3 convolutional filter across layers, helping it be effective at capturing fine details and smoothing space. This large integrated filter helps learn a rich representation of the input image, thereby improving the performance of many computer vision tasks.
This network ends with 3 fully connected layers that allow collection and subsequent distribution. This algorithm enables VGG19 to learn complex patterns and abstract features, making it very successful at identifying patterns found in images. Capturing process input images with layered representation quality. Its depth and consistency make it capable and effective at many computer vision tasks, including image classification, object detection, and pattern transformation.

V.  NOVELTY

Multimodal transformation is a new extension of neural modality transformation that demonstrates the ability to simultaneously transform multiple performances for a single image. Unlike single-style transformation, which restricts changing the style of a single image, multi-style transformation allows for the combination of different capabilities in a stylized image, providing better design and flexibility. Expanding the diversity of art in photography, it allows users to create unique and compelling works by combining visual elements from different image types. By combining and combining a wide variety of forms of migration, new avenues for exploration and expression in the visual arts are opened. We need to develop new algorithms that balance and prioritize the contributions of various image formats while preserving the original image content. Solving these problems requires new methods, optimization techniques and design models for manufacturing non-functional, leading to exciting different types of changes in computer vision and image processing. Innovation lies in the ability to combine various art forms into a single image, providing an unprecedented opportunity for creative expression and artistic exploration in digital imaging.

VI.  PERFORMANCE COMPARISON

We compared our proposed deep learning (DL) model's experimental findings with those of other DL and transfer learning techniques, including Convolutional Neural Network (CNN), VGG19, and Xception Net, to assess the model's efficacy. Important measures like accuracy, loss, precision, recall, F1 score, Area Under the Curve (AUC), and confusion matrix were used to premise the comparison. Based on all six criteria, VGG19 consistently performed better than CNN and Xception Net, according to our quantitative investigation.
As an example, CNN obtained an accuracy of 93% and a loss of 72%, whereas Xception Net obtained an accuracy of 93% and a loss of 85%.

 

On the other hand, our suggested model performed noticeably better, with an accuracy of 95% and a loss of 17%. This superior performance underscores the efficacy of our approach compared to existing methods, as illustrated in Figure 11.
VII.  CONCLUSION

Our study of different art transfer styles using the VGG19 model represents a significant advance in the field of digital art and neural style transfer. Leveraging VGG19's powerful feature extraction capabilities, we demonstrate its ability to effectively blend various artistic styles into a coherent image. This ability not only enhances the beauty of the final work of art, but also opens up opportunities for artists and designers to experiment and express themselves. The superior performance of our model compared to existing transformation models demonstrates the potential of this multivariate transformation to change the way digital art is made and created. This research opens up exciting opportunities for future research and innovation at the intersection of art and technology.

VII.  FUTURE WORKS
In the continued development of various forms of transmission art, significant progress must be made to improve the creative process. A key area of improvement would be expanding the range of graphics the model can perform simultaneously. This effort requires the development of a discrimination model that can encompass multiple pathways and behavioral nuances. To this end, we are developing a user-friendly interface that will allow artists to adjust the composition of the model according to their creative preferences. This level of control allows performers to create products tailored to their own performances. The purpose of using optimization techniques is to make the process more flexible without compromising the quality of the results. This requires investigating the potential of new convolutional networks and techniques, such as pruning and quantization, to increase speed. such as video, virtual reality, and augmented reality. This expands the scope of art and innovation and increases the impact of science. The goal is to improve the model's ability to combine multiple models while preserving the integrity of the original content. This may include creating new layers or optimizing redundancy to preserve key features of the input content. New dimensions of art are demonstrated through different types of art displacement.

REFERENCES
[1] Zhang, H., & Dana, K. (2018). "Multi-style Generative Network for Real-time Transfer." In Proceedings of the European Conference on Computer Vision (ECCV) Workshops (pp. 0-0).
[2] Gao, W., Li, Y., Yin, Y., & Yang, M.-H. (2020). "Fast Video Multi-Style Transfer." In Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision (WACV) (pp. 3222-3230).



