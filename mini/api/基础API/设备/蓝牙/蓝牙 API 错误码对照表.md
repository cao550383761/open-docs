| **错误码** | **说明** | **解决方案** |
| --- | --- | --- |
| 10000 | 未初始化蓝牙适配器。 | 调用 [my.openBluetoothAdapter](https://opendocs.alipay.com/mini/api/kunuy4)，进行蓝牙适配器初始化。 |
| 10001 | 当前蓝牙适配器不可用。 | 检查当前设备对 BLE 的支持情况，并开启蓝牙功能。 |
| 10002 | 没有找到指定设备。 | 检查 deviceId，并确认已开启目标蓝牙外设的广播。 |
| 10003 | 连接失败。 | 检查 deviceId，并确认已开启目标蓝牙外设的广播。 |
| 10004 | 没有找到指定服务。 | 检查 serviceId，并确认目标外设已拥有该服务。 |
| 10005 | 没有找到指定特征值。 | 确保 characteristicId 正确、检查目标外设特定 service 下已具备该特征。 |
| 10006 | 当前连接已断开。 | 连接断开，重新连接。 |
| 10007 | 当前特征值不支持此操作。 | 检查特征值具备读、写、通知等功能。 |
| 10008 | 其余所有系统上报的异常。 | 其他未知错误，具体问题具体分析。 |
| 10009 | Android 系统特有，系统版本低于 4.3 不支持 BLE。 | 提示用户该安卓系统版本不支持使用 。 |
| 10010 | 没有找到指定描述符。 | 使用正确的 serviceId、characteristicId。 |
| 10011 | 设备 ID 不可用，或为空。 | 使用正确的 deviceId。 |
| 10012 | 服务 ID 不可用，或为空。 | 使用正确的 serviceId。 |
| 10013 | 特征 ID 不可用，或为空。 | 使用正确的 characteristicId。 |
| 10014 | 发送的数据为空或格式错误。 | 确保写数据或者 HEX 转化正确。 |
| 10015 | 操作超时。 | 重新操作。 |
| 10016 | 缺少参数。 | 检查调用的参数，并重新操作。 |
| 10017 | 写入特征值失败。 | 写失败。确保外设特征支持写操作，不要断开连接。 |
| 10018 | 读取特征值失败。 | 读失败。确保外设特征支持读操作，不要断开连接。 |

