# Vietnamese Street Food Dataset
This repository contains the dataset used in the paper:

Multimodal Vision–Language Understanding for Real-Time Multi-Dish Recognition and Semantic-Aware Digital Menu Generation **[[1]](#reference-1)**

Thi Hoa Hue Nguyen, Pham Minh Hoang (Corresponding Author), Vu Dinh Hiep, Nguyen Thi Lan Anh, Duong Thi Huong Tra, Tran Hai Anh
Hanoi University of Industry; Hanoi University of Science and Technology

The International Conference on Intelligent Systems & Networks (ICISN 2026), Hanoi, Vietnam 

# Overview
This dataset contains **approximately 3,500 real-world images** of popular **Vietnamese street food** dishes. The images were collected to support tasks such as image classification, food recognition, and cultural heritage preservation related to Vietnamese cuisine.

All photos focus on authentic street-style presentations — from markets, vendors, and everyday eating spots across Vietnam. The dataset is particularly useful for training models to identify Vietnamese foods in natural, varied conditions (different angles, lighting, backgrounds, and plating styles).

**Hugging Face Dataset Link**: [https://huggingface.co/datasets/HoagMin/Vietnamese_StreetFood_Dataset] 

### Key Features
- **Total images**: ~3,500
- **Classes**: 14 distinct Vietnamese street food dishes
- **Indexing**: Standard 0–13 labels
- **Splits**: train / validation / test (approximately 40% / 30% / 30%)
- **Image quality**: Real-world street photos — variable lighting, angles, and compositions for better generalization

### Class Mapping (0-13 indexing)
| ID | English Name                      | Vietnamese Name     |
|----|-----------------------------------|---------------------|
| 0  | Steamed Rice Rolls                | Bánh cuốn           |
| 1  | Vietnamese pyramid rice dumpling  | Bánh giò            |
| 2  | Grilled Pork Banh Mi              | Bánh mì             |
| 3  | Hue-style Spicy Beef Noodle Soup  | Bún bò Huế          |
| 4  | Grilled Pork with Vermicelli      | Bún chả             |
| 5  | Vermicelli with Tofu              | Bún đậu mắm tôm     |
| 6  | Grilled Pork Vermicelli           | Bún thịt nướng      |
| 7  | Pork Offal Porridge               | Cháo lòng           |
| 8  | Flattened green rice              | Cốm                 |
| 9  | Broken Rice                       | Cơm tấm             |
| 10 | Fried Rice                        | Cơm rang            |
| 11 | Beef Pho                          | Phở bò              |
| 12 | Spring Rolls                      | Gỏi cuốn            |
| 13 | Sticky Rice                       | Xôi                 |

### Dataset Structure
After downloading and unzipping, the directory structure is organized for YOLO training:

```text
dataset/
├── data.yaml       # Configuration file (Classes & Paths)
├── train/
│   ├── images/     # Training images
│   └── labels/     # Training labels (.txt)
├── valid/
│   ├── images/     # Validation images
│   └── labels/     # Validation labels (.txt)
└── test/
    ├── images/     # Test images
    └── labels/     # Test labels (.txt)
```

### References

* <a id="reference-1"></a>**[1]** **Multimodal Vision–Language Understanding for Real-Time Multi-Dish Recognition and Semantic-Aware Digital Menu Generation**.  
  [https://drive.google.com/file/d/1BiDtCMCUqDWNfOHG_SkVuKDxwZjD-DSk/view?usp=sharing]
