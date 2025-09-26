# Audio CNN

## Features:

- 🧠 Deep Audio CNN for sound classification
- 🧱 ResNet-style architecture with residual blocks
- 🎼 Mel Spectrogram audio-to-image conversion
- 🎛️ Data augmentation with Mixup & Time/Frequency Masking
- ⚡ Serverless GPU inference with Modal
- 📊 Interactive Next.js & React dashboard
- 👁️ Visualization of internal CNN feature maps
- 📈 Real-time audio classification with confidence scores
- 🌊 Waveform and Spectrogram visualization
- 🚀 FastAPI inference endpoint
- ⚙️ Optimized training with AdamW & OneCycleLR scheduler
- 📈 TensorBoard integration for training analysis
- 🛡️ Batch Normalization for stable & fast training
- 🎨 Modern UI with Tailwind CSS & Shadcn UI
- ✅ Pydantic data validation for robust API requests

## Demo

🌐 **Try it live:** [https://audio-cnn-six.vercel.app/](https://audio-cnn-six.vercel.app/)

Here are some screenshots showcasing the Audio CNN application in action:

![App Demo 1](assets/Screenshot%202025-09-26%20151404.png)

![App Demo 2](assets/Screenshot%202025-09-26%20151414.png)

![App Demo 3](assets/Screenshot%202025-09-26%20151424.png)

## Setup

Follow these steps to install and set up the project.

### Clone the Repository

```bash
git clone https://github.com/Abi27052000/Audio-CNN.git
```

### Backend

Navigate to folder:

```bash
cd Audio-CNN
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Modal setup:

```bash
modal setup
```

Run on Modal:

```bash
modal run main.py
```

Deploy backend:

```bash
modal deploy main.py
```

### Frontend

Install dependencies:

```bash
cd frontend
npm i
```

Run:

```bash
npm run dev
```
