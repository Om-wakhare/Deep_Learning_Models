# Deep Learning Case Studies

## Project Overview
This repository contains comprehensive deep learning case studies demonstrating various AI/ML techniques including Convolutional Neural Networks (CNNs) for image classification, Large Language Models (LLMs) for text processing, and handwritten digit recognition. Each case study is implemented as a standalone application with professional documentation and industrial standards.

## 🚀 Features
- **Real-time Image Classification**: MobileNetV2-based CNN for live webcam classification
- **Advanced Text Processing**: FLAN-T5 model for summarization and Q&A
- **MNIST Digit Recognition**: Complete CNN pipeline for handwritten digit classification
- **Model Caching**: Intelligent caching systems for optimal performance
- **Professional Documentation**: Industrial-standard README files for each component
- **Modular Architecture**: Independent, well-documented modules

## 📁 Project Structure
```
Dl_casestudies/
├── CNN (Open CV)/                    # Real-time image classification
│   ├── CNN(Open CV).py              # Main application
│   ├── mobilenetv2_model.pkl        # Cached model
│   └── README.md                    # Documentation
├── CNN Edge Detection/               # Advanced CNN implementation
│   ├── CNNEdgeDetection.py          # Main application
│   ├── mobilenetv2_model.joblib     # Cached model
│   └── README.md                    # Documentation
├── HuggingFace LLM/                  # Text processing with FLAN-T5
│   ├── FLAN_T5.py                   # Main application
│   ├── flan_model.joblib            # Cached model
│   ├── flan_tokenizer.joblib        # Cached tokenizer
│   └── README.md                    # Documentation
├── MNIST Handwritten Digit Recognition/  # MNIST digit classification
│   ├── MNIST_CNN.py                 # Main application
│   ├── mnist_cnn_model.h5           # Trained model (auto-generated)
│   ├── training_history.joblib      # Training history (auto-generated)
│   └── README.md                    # Documentation
├── requirements.txt                  # Project dependencies
└── README.md                        # This file
```

## 🛠️ Installation

### Prerequisites
- Python 3.7+
- 8GB+ RAM recommended
- Webcam (for CNN applications)
- Internet connection (for initial model downloads)

### Quick Start
1. **Clone the repository**
   ```bash
   git clone https://github.com/Om-wakhare/Deep_Learning_Models.git
   cd Dl_casestudies
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run any application**
   ```bash
   # Image Classification
   cd "CNN (Open CV)"
   python "CNN(Open CV).py"
   
   # Advanced CNN
   cd "../CNN Edge Detection"
   python CNNEdgeDetection.py
   
   # Text Processing
   cd "../HuggingFace LLM"
   python FLAN_T5.py
   
   # MNIST Digit Recognition
   cd "../MNIST Handwritten Digit Recognition"
   python MNIST_CNN.py
   ```

## 📊 Case Studies

### 1. Real-time Image Classification (CNN + OpenCV)
**Location**: `CNN (Open CV)/`

**Description**: Implements real-time object classification using MobileNetV2 and OpenCV. Captures live video from webcam and provides instant classification results.

**Key Features**:
- Live webcam processing
- MobileNetV2 pre-trained model
- Model caching with joblib
- Real-time confidence scores

**Usage**:
```bash
cd "CNN (Open CV)"
python "CNN(Open CV).py"
```

### 2. Advanced CNN Implementation
**Location**: `CNN Edge Detection/`

**Description**: Advanced implementation of MobileNetV2 with enhanced caching, error handling, and professional logging.

**Key Features**:
- Advanced model caching
- Robust error handling
- Professional logging
- Optimized performance

**Usage**:
```bash
cd "CNN Edge Detection"
python CNNEdgeDetection.py
```

### 3. Text Processing with FLAN-T5
**Location**: `HuggingFace LLM/`

**Description**: Comprehensive text processing system using Google's FLAN-T5 model for summarization and question answering.

**Key Features**:
- Text summarization
- Context-based Q&A
- Interactive interface
- Advanced model caching

**Usage**:
```bash
cd "HuggingFace LLM"
python FLAN_T5.py
```

### 4. MNIST Handwritten Digit Recognition
**Location**: `MNIST Handwritten Digit Recognition/`

**Description**: Complete CNN pipeline for MNIST handwritten digit recognition including training, evaluation, and prediction capabilities.

**Key Features**:
- Custom CNN architecture
- Data augmentation
- Model training and evaluation
- Comprehensive visualizations
- Model persistence

**Usage**:
```bash
cd "MNIST Handwritten Digit Recognition"
python MNIST_CNN.py
```

## 🔧 Technical Specifications

### Dependencies
- **Core**: NumPy, OpenCV, TensorFlow
- **NLP**: Transformers, PyTorch, Tokenizers
- **Visualization**: Matplotlib, Seaborn
- **Utilities**: Joblib, Pillow, Scikit-learn
- **Development**: Jupyter, IPython

### Performance Metrics
- **CNN Applications**: ~30 FPS processing
- **LLM Applications**: ~2-5 seconds per request
- **MNIST Training**: ~30-60 minutes (CPU), ~5-15 minutes (GPU)
- **Model Sizes**: 14MB (CNN), 300MB (LLM), 2-5MB (MNIST)
- **Memory Usage**: 200MB-4GB depending on application

## 📚 Documentation

Each case study includes comprehensive documentation:
- **Installation Instructions**: Step-by-step setup
- **Usage Examples**: Practical usage scenarios
- **Architecture Details**: Technical implementation
- **Troubleshooting**: Common issues and solutions
- **Performance Metrics**: Benchmarks and optimization tips

## 🎯 Use Cases

### Image Classification
- **Security Systems**: Real-time object detection
- **Quality Control**: Automated product inspection
- **Educational**: Learning computer vision concepts
- **Prototyping**: Rapid AI application development

### Text Processing
- **Content Management**: Automated text summarization
- **Customer Support**: Context-aware Q&A systems
- **Research**: Document analysis and processing
- **Education**: Interactive learning tools

### Handwritten Digit Recognition
- **Document Processing**: Automated digit extraction
- **Educational**: Learning CNN fundamentals
- **Research**: Computer vision experiments
- **Prototyping**: OCR system development

## 🚀 Getting Started

### For Image Classification
1. Ensure webcam is connected
2. Run the CNN application
3. Point camera at objects
4. View real-time classifications

### For Text Processing
1. Run the FLAN-T5 application
2. Choose summarization or Q&A mode
3. For Q&A: Create `context.txt` with your content
4. Process text or ask questions

### For MNIST Recognition
1. Run the MNIST application
2. Wait for model training to complete
3. View training progress and results
4. Use trained model for predictions

## 🔍 Advanced Features

### Model Caching
- **Automatic Caching**: Models cached after first download/training
- **Performance Optimization**: Faster startup times
- **Error Recovery**: Automatic fallback mechanisms

### Error Handling
- **Robust Error Recovery**: Graceful handling of failures
- **Informative Logging**: Detailed error messages
- **User Guidance**: Clear troubleshooting instructions

### Performance Optimization
- **Memory Management**: Efficient resource usage
- **Processing Optimization**: Optimized inference pipelines
- **Caching Strategies**: Intelligent model persistence

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add comprehensive documentation
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👨‍💻 Author

**Om Ravindra Wakhare**  
Date: 18/09/2025

## 📞 Support

For issues and questions:
- Create an issue in the repository
- Check individual README files for specific guidance
- Contact the author for direct support

## 🔮 Future Enhancements

- [ ] Web interface for all applications
- [ ] Docker containerization
- [ ] API endpoints for integration
- [ ] Additional model support
- [ ] Performance monitoring tools
- [ ] Automated testing suite
- [ ] Cloud deployment guides
- [ ] Real-time webcam digit recognition
- [ ] Custom dataset support

## 📈 Version History

- **v1.0.0** (18/09/2025): Initial release with comprehensive case studies

---

**Note**: This project demonstrates professional software development practices with comprehensive documentation, error handling, and performance optimization suitable for industrial applications.