# Vehicle Counting System
This is a research project that has a goal for creating an application that can be used to count vehicle flow in roads . This project used YOLO algorithm for detecting vehicles and SORT algorithm for treacking objects.

**Accuration Model:**
| Filename    | TP  | FP | TN | FN | Precision | Recall | F1 Score | Link                         |
|-------------|-----|----|----|----|-----------|--------|----------|------------------------------|
| test-day-1  | 43  | 6  | 3  | 21 | 0.88      | 0.67   | 0.76     | https://youtu.be/voKHGxww8z0 |
| test-day-2  | 81  | 17 | 3  | 62 | 0.83      | 0.57   | 0.67     | https://youtu.be/bVbZ0npyMHg |
| test-day-3  | 101 | 16 | 0  | 8  | 0.86      | 0.93   | 0.89     | https://youtu.be/BnlHyIyYLGU |
| test-day-4  | 79  | 14 | 2  | 30 | 0.85      | 0.72   | 0.78     | https://youtu.be/CymZhwv5Ua0 |
| test-day-6  | 46  | 6  | 2  | 31 | 0.88      | 0.60   | 0.71     | https://youtu.be/DJlXKaJGUls |
| test-day-8  | 35  | 24 | 2  | 0  | 0.59      | 1.00   | 0.74     | https://youtu.be/SEtA39u40D4 |
| test-day-10 | 151 | 17 | 1  | 9  | 0.90      | 0.94   | 0.92     |                              |

**How to use:**
1. Download the tflite model from source https://drive.google.com/drive/folders/1QAH53oghpA64ZugPK4hGR1ApMEAw7UvR?usp=sharing
2. Create vitrual enivironment  `python3 -m virtualenv env`
3. Get all dependencies `pip install -r  requirments.txt`
4. Use command `python video_.py <video source> <virtual zone source> [<export path> <tflite model path> <classname model path>]`

**Download video and vitrual zone sample:** 
https://drive.google.com/drive/folders/16oDzZlZZXfNL3yDOkunn9EuRReMm
