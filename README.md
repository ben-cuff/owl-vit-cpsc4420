# OWL-ViT COCO Evaluation - CPSC4420

## Setup

### 1. Clone the Repository

```bash
git clone https://github.com/ben-cuff/owl-vit-cpsc4420.git
cd owl-vit-cpsc4420
```

### 2. Create Virtual Environment

```bash
python3 -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Download COCO Dataset

```bash
# Download validation images (778MB)
wget http://images.cocodataset.org/zips/val2017.zip
unzip val2017.zip

# Download annotations (241MB)
wget http://images.cocodataset.org/annotations/annotations_trainval2017.zip
unzip annotations_trainval2017.zip
```

```bash
# Download validation images
curl -O http://images.cocodataset.org/zips/val2017.zip
unzip val2017.zip

# Download annotations
curl -O http://images.cocodataset.org/annotations/annotations_trainval2017.zip
unzip annotations_trainval2017.zip
```