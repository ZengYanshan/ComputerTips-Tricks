# VSCode 操作技巧



##### 调整代码格式

`Alt` + `Shift` + `F`

##### 复制整行

`Alt` + `Shift` + `Down`

该方法不占用剪贴板



### 常见问题

##### 打开 SVG 时显示为图像，而希望编辑源代码

![image-20250217120136230](./assets/image-20250217120136230.png)

**解释：**

在 1.97 版本以后，VSCode 默认以内置的图像预览方式打开 SVG 文件。

**解决：**

右键 SVG 文件 - `Open With...` - `Text Editor`

![image-20250217120548516](./assets/image-20250217120548516.png)

![image-20250217120633369](./assets/image-20250217120633369.png)

![image-20250217120658187](./assets/image-20250217120658187.png)

如果想要设置默认以文本编辑器打开 SVG ，打开设置，找到 `Workbench: Editor Associations` 项，点击 `Add Item` ，输入 `*.svg` 和 `default` 。

![image-20250217120908842](./assets/image-20250217120908842.png)

![image-20250217121100544](./assets/image-20250217121100544.png)

也可以打开设置 JSON 文件，加入以下内容：

```json
"workbench.editorAssociations": {
  "*.svg": "default"
}
```

