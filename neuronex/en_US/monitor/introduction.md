# 数据监控

点击左侧的`数据监控`，选择南向设备和组名称，查看点位数值。

* 南向设备：选择想要查看的南向设备，例如，选择已创建的设备 modbus-tcp-1;
* 组名称：选择想要查看的南向设备下的组，例如，选择已创建的组 group-1；
* 数据监控以组为单位显示数值，页面将会展示读取到的组内每个标签的值。

## 反控设备

### 更改值

当点位为写属性时，数据监控界面的 Tag 会有一个写操作，点击 `Write` 可以实现反控设备，例如，修改具有写属性的 1!40001 点位地址的值，如下图所示。

![write](./_assets/write.png)

* 单击要改值的标签末尾的`写`按键；
* 选择是否以十六进制方式输入，不选择；
* 输入标签新值，例如，123；
* 单击`提交`按键提交新的值。

::: tip
设备中该点位也必须具有可写属性，否则无法写成功。
:::

### 查看设备点位值是否修改成功

打开 Modbus 模拟器，查看点位值是否变化，如下图所示。

![Monitor](./_assets/monitor.png)