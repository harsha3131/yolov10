# YOLOv8 - OpenCV

Implementation YOLOv8 on OpenCV using ONNX Format.

Just simply clone and run

```bash
pip install -r requirements.txt
python main.py --model yolov8n.onnx --img image.jpg
```

If you start from scratch:

```bash
pip install ultralytics
yolo export model=yolov8n.pt imgsz=640 format=onnx opset=12
```

*Make sure to include "opset=12"

---

### About the Maintainer

This project is currently maintained by **Sri Harsha Joshi**. As a Java Full Stack Developer with 4+ years of experience, Sri Harsha is dedicated to architecting, developing, and optimizing robust software solutions. With a strong background in various technologies and a commitment to code quality and continuous integration, he ensures this project remains functional and up-to-date.

Connect with Sri Harsha:
- Email: harshajoshi3103@gmail.com
- GitHub: [Your GitHub Profile]
- LinkedIn: [Your LinkedIn Profile]