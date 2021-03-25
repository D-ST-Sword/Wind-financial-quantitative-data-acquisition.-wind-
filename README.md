# Wind financial quantitative data acquisition.-Wind-
wind : use python to download data (wind 平台提供API接口给python 进行数据收集 方便进行金融量化研究。)
    
    运行环境：
    python == 3.6
    (any version of python could be ok)
    
    在wind的API使用说明中可以看到下面这段，这是使用puyhon wind接口必须要做的操作.
    from WindPy import w
    import pandas as pd
    from datetime import timedelta, date
    w.start()
