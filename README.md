# Laboratory-Work-2-A-Plant-Species-Image-Classification
## Cereal Crops

<img width="620" height="851" alt="image" src="https://github.com/user-attachments/assets/c8ed46a8-2712-4efd-96cd-50a633f513c8" /> I selected 50 epochs to give the model enough time to fully understand the patterns in the dataset. By allowing the model to go through the training data multiple times, it improves its ability to classify images correctly while still avoiding excessive training that could lead to overfitting. This number of epochs helped the model reach high accuracy while maintaining stable performance throughout the training process.

I chose a batch size of 16 because it provides a good balance between learning stability and training efficiency. With this batch size, the model updates its weights after processing a small group of data, which helps make the learning process smoother and more consistent. It is not too small to cause unstable learning and not too large to slow down computation or require too much memory.

The learning rate of 0.001 was selected to ensure gradual and controlled learning. A smaller learning rate allows the model to adjust its weights carefully, reducing the risk of overshooting the optimal solution. Based on the training results, where the accuracy improved quickly and the loss decreased steadily, these chosen values were appropriate and contributed to the model’s strong and stable performance.


Overall, these settings were selected to achieve good accuracy while maintaining stable and efficient training.

## 🌾 Cereal Classification Dataset

| Image | Crop Name |
|:-----:|:---------:|
| <img src="https://github.com/user-attachments/assets/40980c22-87f1-471a-bcfa-e831fac7b73e" width="250" /> | Finger Millet |
| <img src="https://github.com/user-attachments/assets/e8af36f1-e96e-44cf-9267-1cc91cc4d84d" width="250" /> | Corn (Maize) |
| <img src="https://github.com/user-attachments/assets/29be8a61-9824-420d-bd6e-f3999406b290" width="250" /> | Rye |
| <img src="https://github.com/user-attachments/assets/38fd7a02-1e03-4015-b7d4-c4e53d1b92dc" width="250" /> | Pearl Millet |
| <img src="https://github.com/user-attachments/assets/34a6728a-535f-4f3b-b21d-e15989d6be60" width="250" /> | Rice |
| <img src="https://github.com/user-attachments/assets/cbbb761d-111b-4868-920d-17a7df7353ef" width="250" /> | Barley |
| <img src="https://github.com/user-attachments/assets/2c03d044-3917-47a2-ae74-5ccc9b537004" width="250" /> | Oats |
| <img src="https://github.com/user-attachments/assets/4ad8870e-ca91-44de-a48d-01918d71bf4b" width="250" /> | Crop Name |
| <img src="https://github.com/user-attachments/assets/d7cc803f-43a1-4405-939f-6cadd3a47e2e" width="250" /> | Crop Name |
| <img src="https://github.com/user-attachments/assets/a51a5023-bee9-4ef9-b947-ed5a5e852800" width="250" /> | Crop Name |

