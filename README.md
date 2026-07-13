# 🚗 车辆检测系统 - YOLOv8

基于 Roboflow 自定义数据集训练的车辆检测模型，支持小汽车、电动车、卡车等多种目标检测。

## 在线演示

**[🔗 点击体验在线 Demo](https://d6c67bfc55b18bc2e9.gradio.live)**
**Demo 链接**：https://d6c67bfc55b18bc2e9.gradio.live

## 项目展示

### Demo 界面
![Demo 界面](vehicle-detection-project/demo_interface_full.png)

### 不同置信度阈值对比
![置信度对比](vehicle-detection-project/confidence_comparison_3levels_01.png)

**结论**：置信度 **0.40** 是本模型的较优阈值，在准确率和召回率之间取得了良好平衡。

### 检测效果示例
![检测示例](vehicle-detection-project/detection_example_01.png)

## 模型性能

- **mAP@50**：99.1%
- **Precision**：99.2%
- **Recall**：97.5%
- **F1 Score**：97.8%

## 技术栈

- **模型**：YOLOv8 (Roboflow 3.0)
- **框架**：Ultralytics
- **部署方式**：Gradio Web Demo
- **数据集**：自定义车辆数据集（347 张图片）

## 未来改进计划

- 增加更多类别（公交车、特殊车辆）
- 实现实时视频流检测
- 尝试部署到移动端

---
