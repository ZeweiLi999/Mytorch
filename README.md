# 项目介绍


我们要实现的最终项目如下图所示：

![image](https://github.com/user-attachments/assets/8b84bb34-98d1-457a-9c7f-411de6c2b7af)


<!-- 
```
Large_Model_From_None
    ├─Document_module
    ├─llma3
        ├─llam3_from_Pytorch    #用Pytorch实现llma3
        ├─llma3_from_Mytorch    #用Mytorch实现llma3
    └─Mytorch
        ├─Core                  #Mytorch核心代码
        ├─Test                  #Mytorch测试代码
```
-->

```mermaid
graph TD
    Large_Model_From_None --> Document_module
    Large_Model_From_None --> llma3
    Large_Model_From_None --> Mytorch

    llma3 --> llam3_from_Pytorch["llam3_from_Pytorch<br>用Pytorch实现llma3"]
    llma3 --> llam3_from_Mytorch["llma3_from_Mytorch<br>用Mytorch实现llma3"]

    Mytorch --> Core["Core<br>Mytorch核心代码"]
    Mytorch --> Test["Test<br>Mytorch测试代码"]
```
