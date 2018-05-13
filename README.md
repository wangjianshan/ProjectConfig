# 文件配置类

```
    程序初始化的时候, 统一读取配置信息, 然后将其保存到一个 `settings` 类中, 之后无需重复读取.
    
    应用程序配置, 理应统一规划, 避免散落在代码中.
    
    例如运行 `manage.py`
        
        统一读取并规划到 `LazySettings` 类中, 整齐划一, 程序运行中, 都去该配置对象中读取
```