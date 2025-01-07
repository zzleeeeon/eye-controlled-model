# Eye-Controlled 3D Model Viewer

这是一个基于Web的3D模型查看器，使用眼动追踪技术来控制相机视角。该项目使用了Three.js进行3D渲染，并结合了MediaPipe的FaceMesh进行眼动追踪。

## 功能

- **3D模型加载**：使用GLTFLoader加载并显示`car.glb`模型。
- **眼动追踪**：通过摄像头捕捉用户的面部特征，使用MediaPipe的FaceMesh进行眼动追踪。
- **相机控制**：根据用户的眼睛位置动态调整相机视角，使相机始终对准3D模型。
- **全屏显示**：提供全屏按钮，用户可以切换全屏模式以获得更好的观看体验。
- **环境设置**：添加了光源和环境纹理，以增强3D场景的视觉效果。

## 使用方法

1. **克隆仓库**：
   ```bash
   git clone https://github.com/zzleeeeon/eye-controlled-model.git 


2. **导航到项目目录**：
   ```bash
   cd eye-controlled-model
   ```

3. **打开`index.html`**：
   - 使用浏览器打开`index.html`文件即可查看Demo。

## 依赖

- [Three.js](https://threejs.org/)
- [MediaPipe FaceMesh](https://google.github.io/mediapipe/solutions/face_mesh.html)

## 注意事项

- 确保您的浏览器支持WebGL和摄像头访问。
- 在iOS设备上访问时，请确保使用HTTPS连接。
- 如果在移动设备上使用，可能需要调整摄像头权限设置。

## 贡献

欢迎提交问题和请求。如果您有任何改进建议或功能请求，请通过GitHub Issues与我们联系。

## 许可证

该项目使用MIT许可证。有关详细信息，请参阅LICENSE文件。