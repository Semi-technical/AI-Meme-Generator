# 🎭 AI Meme Generator

An intelligent meme generator powered by AI that creates funny memes automatically using GPT-2 and computer vision.

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![ML](https://img.shields.io/badge/ML-Transformers-green.svg)
![Status](https://img.shields.io/badge/Status-Active-success.svg)

## 🌟 Features

- 🤖 **AI-Powered Caption Generation** - Uses GPT-2 transformer model to create contextual humor
- 🖼️ **35+ Meme Templates** - Popular formats including Drake, Distracted Boyfriend, Disaster Girl, and more
- 🎨 **5 Caption Styles** - Funny, Sarcastic, Relatable, Wholesome, Chaos
- 📹 **Video Meme Support** - Add AI-generated captions to MP4/AVI/MOV videos
- 🎞️ **GIF Support** - Create animated memes with text overlays
- 🌐 **Interactive Web Interface** - User-friendly Gradio interface
- ⚡ **Fast Generation** - Creates memes in under 3 seconds

## 🚀 Quick Start

### Run in Google Colab (Recommended)

1. Click on the `.ipynb` notebook file above
2. Click "Open in Colab" button
3. Run all cells (Runtime → Run all)
4. Wait for the Gradio interface to load
5. Start creating memes!

### Local Installation
```bash
# Clone repository
git clone https://github.com/YOUR_USERNAME/AI-Meme-Generator.git
cd AI-Meme-Generator

# Install dependencies
pip install transformers torch pillow gradio moviepy imageio

# Run the notebook
jupyter notebook
```

## 💡 How to Use

### AI Mode:
1. Enter a topic (e.g., "Monday morning", "college exams", "coding bugs")
2. Select a meme template from the dropdown
3. Choose a caption style (funny, sarcastic, relatable, etc.)
4. Click "Generate Meme"
5. Download and share!

### Manual Mode:
1. Switch to "Manual Text" mode
2. Enter your own top and bottom text
3. Select a template
4. Generate!

## 🎯 Example

**Input:**
- Topic: "Monday morning"
- Style: Sarcastic
- Template: Drake

**Output:**
- Top Text: "Me on Sunday night"
- Bottom Text: "Remembering Monday exists"

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **Python 3.8+** | Core programming language |
| **PyTorch** | Deep learning framework |
| **Transformers (Hugging Face)** | GPT-2 model for text generation |
| **Pillow (PIL)** | Image processing and text overlay |
| **Gradio** | Web interface creation |
| **MoviePy** | Video processing |
| **ImageIO** | GIF handling |

## 📊 Project Architecture
```
AI Meme Generator
│
├── Text Generation (NLP)
│   ├── GPT-2 Model
│   ├── Multiple Style Prompts
│   └── Caption Refinement
│
├── Image Processing (CV)
│   ├── Template Selection
│   ├── Text Overlay Engine
│   └── Font Rendering
│
├── Video Processing
│   ├── Video Text Overlay
│   └── GIF Generation
│
└── User Interface
    ├── Gradio Web App
    └── Interactive Controls
```

## 🎓 Educational Value

This project demonstrates practical applications of:

- **Natural Language Processing (NLP)** - Text generation using transformers
- **Computer Vision** - Image manipulation and text rendering
- **Machine Learning** - Pre-trained model integration
- **Software Engineering** - Clean code, modularity, documentation
- **UI/UX Design** - User-friendly interface creation

## 📁 Project Structure
```
AI-Meme-Generator/
├── AI_Meme_Generator.ipynb    # Main notebook
├── meme_templates/             # 35+ meme template images
│   ├── drake.jpg
│   ├── distracted_boyfriend.jpg
│   └── ...
├── README.md                   # This file
└── generated_memes/            # Output folder (created at runtime)
```

## 🔧 How It Works

1. **Input Processing**: User provides topic or custom text
2. **AI Generation**: GPT-2 analyzes context and generates humorous caption
3. **Text Splitting**: Caption divided into top and bottom text
4. **Template Selection**: Appropriate meme template chosen
5. **Image Processing**: Text overlaid with proper styling (white text, black outline)
6. **Output**: Final meme ready for download and sharing

## 🎨 Supported Meme Templates

Drake, Two Buttons, Distracted Boyfriend, Change My Mind, Disaster Girl, Hide the Pain Harold, Success Kid, Bad Luck Brian, Expanding Brain, Woman Yelling at Cat, Surprised Pikachu, Is This a Pigeon, Mocking SpongeBob, Ancient Aliens, Philosoraptor, Evil Kermit, Left Exit 12, Running Away Balloon, Always Has Been, Doge, Trade Offer, Spider-Man Pointing, Leonardo DiCaprio, Boardroom Meeting, First World Problems, Math Lady, The Rock Driving, Waiting Skeleton, This Is Fine, UNO Draw 25, and many more!

## 📈 Performance

- ⚡ Generation Speed: < 3 seconds per meme
- 🎯 Template Library: 35+ templates
- 🤖 AI Models: GPT-2, DistilGPT-2, GPT-2 Medium
- 📊 Caption Quality: Context-aware and humorous

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Add more meme templates
- Improve AI caption quality
- Enhance the UI
- Fix bugs
- Add new features

## 📝 License

This project is open source and available under the MIT License.

## 🙏 Acknowledgments

- Hugging Face for transformer models
- Imgflip for meme templates
- The meme community for inspiration
- My college professors for guidance

## 📧 Contact

**Created by:** [KUNJ DARJI]  
**College:** [LDRP-ITR]  
**Year:** 2024  
**Course:** Machine Learning / Computer Science  

Feel free to reach out for questions or collaborations!

---

⭐ **If you found this project helpful, please give it a star!** ⭐

Made with ❤️ and AI
```

### **Step 4: Customize**

**IMPORTANT:** Replace these parts with YOUR information:

Find these lines and change them:
```
git clone https://github.com/Semi-technical/AI-Meme-Generator.git

**Created by:** [KUNJ DARJI]  

**College:** [LDRP-ITR]  
```

### **Step 5: Save It**

1. Scroll down to the bottom
2. You'll see a box that says "Commit new file"
3. Click the green **"Commit new file"** button

---

## **🎉 CONGRATULATIONS! You're Done!**

Your project is now **completely uploaded** and looks **professional**!

---

## **What You Have Now:**

✅ GitHub repository with all files  
✅ Professional README with badges and formatting  
✅ Your meme generator code  
✅ All meme templates  
✅ Portfolio-ready project  

---

## **Your Repository Link:**

Your project is at:
```
https://github.com/Semi-technical/AI-Meme-Generator
```

**Copy this link** and save it! You'll use it for:
- Resume
- LinkedIn
- College submission
- Job applications

---

## **Final Steps (Optional but Recommended):**

### **1. Add Topics to Your Repo**

1. On your repository page, look for **"About"** section (right side)
2. Click the ⚙️ gear icon
3. Add these topics (tags):
```
   machine-learning
   artificial-intelligence
   meme-generator
   nlp
   computer-vision
   python
   deep-learning
   gpt-2
   gradio
   college-project
