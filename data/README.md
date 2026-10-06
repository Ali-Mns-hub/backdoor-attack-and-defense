# Data Setup

This project uses the **CIFAR-10 dataset** for training both the backdoored model and the cleansed student model.

*   **Source:** The dataset is automatically downloaded via `torchvision.datasets.CIFAR10` during the notebook execution[cite: 94, 113].
*   No manual download is required. The script will create a `./data/cifar10/` directory and extract the necessary files automatically.
*   **Unlabeled Data:** For the distillation phase, a subset of the data is used without its labels to simulate a real-world defense scenario[cite: 99, 115].
