#### **Project Overview**
This repository contains the implementation of a CS786 assignment focused on reproducing and extending experiments from the Yan & Zhou (2017) paper. The goal is to explore the ability of Convolutional Neural Networks (CNNs) to understand Gestalt principles such as symmetry, proximity, and closure. The tasks have been implemented using Inception v4 networks and synthetic datasets.  

---

#### **Repository Structure**
```
├── CS786_A3_Q1_Q2.ipynb     # Implementation for Q1 and Q2
├── Q3/
│   ├── CS786_A3_Q3.ipynb    # Implementation for Q3 (Proximity principle)
│   ├── dataset/             # Synthetic dataset for proximity experiments
├── CS786_A3_Q4.ipynb        # Implementation for Q4 (Closure principle)
└── README.md                # Project documentation
```

---

#### **Tasks and Descriptions**

1. **Q1: Study Design Reproduction with Inception v4**
   - Reproduced the study design steps from Yan & Zhou (2017), originally implemented with Inception v3, using Inception v4 networks.  
   - Includes training and evaluation steps.  
   - Refer to: `CS786_A3_Q1_Q2.ipynb`

2. **Q2: Symmetry Principle**
   - Reproduced results for global symmetry using the synthetic dataset provided in the paper.
   - Verified CNN's capability to learn symmetry concepts.
   - Refer to: `CS786_A3_Q1_Q2.ipynb`

3. **Q3: Proximity Principle**
   - Explored the Gestalt principle of proximity by designing macro-objects using densely packed micro-objects.
   - Gradually increased spacing between micro-objects over successive training rounds to achieve proximity generalization.
   - Dataset and code available in the `Q3/` directory.
   - Refer to: `Q3/CS786_A3_Q3.ipynb`

4. **Q4: Closure Principle**
   - Investigated the closure principle by designing training and testing strategies to classify macro-objects with varying degrees of "closed" configurations.
   - Refer to: `CS786_A3_Q4.ipynb`

---

#### **Setup and Requirements**

1. Install dependencies:
   - Python 3.x
   - TensorFlow/Keras
   - NumPy, Matplotlib, and other standard data science libraries

2. Clone the repository and navigate to the folder:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

3. Run each notebook in a Jupyter environment:
   - Ensure the datasets for Q3 are correctly placed in the `Q3/dataset/` folder.

---

#### **Acknowledgements**
This project is based on the Yan & Zhou (2017) paper and builds upon the datasets and code provided by the authors.

For any queries, contact [Your Name/Email].
