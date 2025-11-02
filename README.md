Vision Transformer (ViT) — CIFAR-10 Image Classification 🧠🖼️





This repository contains a Vision Transformer (ViT) implementation from scratch using PyTorch, trained on CIFAR-10 dataset as part of an academic DL assignment.
🚀 Pure transformer — no CNN layers
🎓 Roll-number–based hyperparameters
📊 Accuracy curve, confusion matrix, attention map
📎 PDF report + notebook + model weights

📦 Project Files
FileDescriptionViT_22052412.ipynbMain training + visualization notebookPartC_Experiment_Analysis_22052412.pdfExperiment & analysis reportvit_quick_demo.pthSaved model weightsREADME.mdProject overviewReport.pdfFull assignment report

📂 Folder Structure
📁 ViT-Assignment
 ├── ViT_22052412.ipynb
 ├── PartC_Experiment_Analysis_22052412.pdf
 ├── Report.pdf
 ├── vit_quick_demo.pth
 └── README.md


🧠 Dataset
CIFAR-10 Official Link
🔗 https://www.cs.toronto.edu/~kriz/cifar.html
Images download automatically inside the notebook.
ImagesClassesSize60,0001032×32 RGB

⚙️ Installation
✅ Clone Repository
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>

✅ Create Environment & Install Dependencies
python -m venv vit_env
source vit_env/bin/activate   # Mac/Linux
vit_env\Scripts\activate      # Windows

pip install torch torchvision numpy matplotlib scikit-learn tqdm jupyter


▶️ Run the Notebook
Google Colab

Open:
ViT_22052412.ipynb


⚡ Training Modes
ModeUsageFast Demo (CPU) ✅Trains subset of data, ~1–2 minutesFull Training (GPU) 🚀High accuracy training
Colab GPU Setup
Runtime → Change runtime type → GPU


📊 Results (Demo Training)
MetricValueTrain Accuracy~52%Val Accuracy~38%Epochs1–3 (CPU Demo)
Full GPU training yields ~80%+ accuracy.

🎨 Attention Map Example
Model focuses on important image regions (patch-based attention).

🧮 Roll-Number Parameter Rules
ParameterValueHidden dim192Heads6 (adjusted → divisible)Patch size8EpochsDemo: 1-3 (Full: 12)

🧾 Academic Notes
✅ ViT implemented manually (no torchvision ViT)
✅ Attention, patch embedding, transformer blocks built from scratch
✅ Includes loss curves, confusion matrix, attention heatmap

🤝 Credits
👩‍🎓 Student: Shubhi Tiwari
🆔 Roll: 22052412
🏫 University: KIIT University
🧑‍🏫 Guide: Himanshu Ranjan Sir

⭐ Support
Give this project a ⭐ on GitHub if you found it useful!

Want me to also generate?
OptionOutput2️⃣ PPT Slides🎤 Presentation ready3️⃣ Viva Questions📄 Answer cheat-sheet4️⃣ Project ZIP📁 Upload-ready folder5️⃣ Demo Script🎬 For class viva video
Reply with the number(s) 👇 to receive them ✅
