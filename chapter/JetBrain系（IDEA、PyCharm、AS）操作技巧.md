# JetBrain系（IDEA、PyCharm、AS）操作技巧



##### 查看源码

1. `Ctrl` + `Mouse Left`：跳转到对应声明或源码（跳转途径的文件不保留在菜单）
2. double `Shift`：查找，然后跳转到源码。可根据文件名查找。

##### 注释

- `Ctrl` + `/`

##### 快捷代码

- `psvm` ：标准 `main` 函数
- `.var `：接收返回值
- `sout` ：输出
- `itit` ：迭代器循环
- `foreach` ：`foreach` 循环
- `stful` ：快速创建 `StatefulWidget` 及其对应 `State` 类

##### 连带创建目录

- `parentDirectoryName.directoryName.fileName`：新建文件
- `grandparentDirectoryName/parentDirectoryName/directoryName`：新建目录
  > 若用类似新建文件的方法，会新建一个名字带`.`的目录

##### 调整缩进

- `Ctrl` + `Alt` + `L`：调整全文缩进
- `Ctrl` + `Alt` + `I`：调整选中部分缩进

##### 批量改名

- `shift` + `F6` ( + `Enter`)



### 常见问题

##### .java文件图标左下角有橙色j且main函数不能运行

**解释：**未设置 `Source` 目录，IDEA无法识别

**解决：**
- 右键 `src` - `Mark Directory as` - `Sources Root`
- `file` - `Project Structure` - `Modules` - 右大栏 `Sources` - 单击 `src` - `Mark as` 单击 `Sources`

#### Spring Boot

##### `@Autowired`报错但实际有Java Bean

**解决：**
- `File` - `Settings` - `Editor` - `Inspections` - `Spring` - `Spring Code` - `Code`，找到对应项并调为`Warning`

##### Markdown代码&预览窗口变为上下排布

![image-20250211213423093](./assets/image-20250211213423093.png)

**解决：**

- 再点一下右上角的`Editor and Preview`按钮

![image-20250211213524645](./assets/image-20250211213524645.png)

##### 行号栏左侧出现Git的修改记录

![image-20250211213706930](./assets/image-20250211213706930.png)

**解决：**

- 在左栏处右键 - `关闭注解`

![image-20250211213958000](./assets/image-20250211213958000.png)

- 如需打开，在行号栏处右键 - `使用 Git 追溯注解`

![image-20250211214103601](./assets/image-20250211214103601.png)