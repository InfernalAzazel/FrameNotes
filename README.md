## 框架笔记

### 编程语言
- ### [Python]()
  - #### web
    1. [Django](https://www.djangoproject.com/) - 重量级 web 框架集成很多功能开箱即用，缺点不灵活。
    2. [Flask](https://flask.palletsprojects.com/en/1.1.x/) - 轻量级 web 框架，灵活，但是需要自己实现很多功能。
    3. [Tornado](https://www.tornadoweb.org/en/stable/) - 异步 web 框架，性能好。
    4. [Sanic](https://sanic.readthedocs.io/en/latest/) - 异步 web 框架，性能好，但是文档不全，社区不活跃。
    5. [FastAPI](https://fastapi.tiangolo.com/) - 异步 web 框架，性能好，文档全，社区活跃，但是功能不全，需要自己实现很多功能。[推荐: 挺好用, 效率高，性能高， 简洁]()
  - #### 爬虫
    1. [Scrapy](https://scrapy.org/) - 重量级爬虫框架，功能全，但是写代码产生 bug 概率多。[目前: 在使用]()
    2. [requests](https://requests.readthedocs.io/en/master/) - 轻量级爬虫框架，功能少，但是写代码产生 bug 概率少。
    3. [aiohttp](https://docs.aiohttp.org/en/stable/) - 异步爬虫框架，性能好，但是写代码产生 bug 概率多。
    4. [httpx](https://www.python-httpx.org/) - 异步爬虫框架，性能好, 同步异步都支持。 [推荐: 适合需要灵活的爬虫]()
    5. [crawlab](https://github.com/crawlab-team/crawlab.git) - 分布式爬虫管理平台，功能全，但是文档不全，社区不活跃。
    6. [Gerapy](https://github.com/Gerapy/Gerapy.git) - 分布式爬虫管理平台，功能全，但是文档不全,社区不活跃。[注: 每几个月出现bug导致任务无法按时运行]()
  - #### 定时任务 + 分布式
    1. [APScheduler](https://apscheduler.readthedocs.io/en/stable/) - 轻量级定时任务框架，功能全，但是写代码产生 bug 概率多。[符合业务需求的推荐使用]()
    2. [Celery](https://docs.celeryproject.org/en/stable/) - 重量级定时任务框架，功能全，但是写代码产生 bug 概率多。 [注: 长期运行的任务支持差]()
    3. [Ray](https://docs.ray.io/en/latest/) - 分布式任务框架，高性能，功能全，亲和 AI 训练 爬虫等。[推荐: 使用]()
  - #### 数据处理
    1. [pydantic](https://pydantic-docs.helpmanual.io/) - 数据校验框架，功能全。[推荐: 使用]()
    2. [pandas](https://pandas.pydata.org/) - 数据分析框架。[目前:常用, 处理 excel csv 等不要太舒服了]()
    3. [numpy](https://numpy.org/) - 数学计算框架。
    4. [scipy](https://www.scipy.org/) - 科学计算框架。
    5. [matplotlib](https://matplotlib.org/) - 数据可视化框架。
    6. [seaborn](https://seaborn.pydata.org/) - 数据可视化框架。
  - #### AI
    1. [langchain]() - AI LLM 底层级框架，灵活，提供丰富的功能。
    2. [llama_index]() - 基于 langchain 封装的数据索引 [推荐使用]()
    3. [scikit-learn](https://scikit-learn.org/stable/) - 机器学习框架。
    4. [pytorch](https://pytorch.org/) - 深度学习框架。[推荐: 使用]()
    5. [tensorflow](https://www.tensorflow.org/) - 深度学习框架，功能全。
    6. [keras](https://keras.io/) - 深度学习框架。
    7. [xgboost](https://xgboost.readthedocs.io/en/latest/) - 机器学习框架。
    8. [lightgbm](https://lightgbm.readthedocs.io/en/latest/) - 机器学习框架。
    9. [catboost](https://catboost.ai/) - 机器学习框架。
  - #### 其他
    1. [typer](https://github.com/tiangolo/typer.git) - 命令行框架，功能全 [推荐: 使用]()
   
- ### [JS&TS]()
  - #### web
    1. [nestjs](https://github.com/nestjs/nest.git) - 重量级 web 框架集成很多功能开箱即用。
    2. [express](https://github.com/expressjs/express.git) - 底层级 web 框架，灵活。
  - #### 爬虫
    1. [crawlee](https://github.com/apify/crawlee.git) - 重量级 web 框架集成很多功能开箱即用。
    2. [apify-sdk](https://github.com/apify/apify-sdk-js.git) - 基于crawlee 爬虫管理平台有一定的免费空间。