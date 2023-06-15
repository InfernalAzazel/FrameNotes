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
    1. [Scrapy](https://scrapy.org/) - 重量级爬虫框架，功能全。[目前: 在使用]()
    2. [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/) - 解析 html 快速提取字符串。
    3. [pyquery](https://github.com/gawel/pyquery.git) - 解析 html 快速提取字符串。[推荐: 使用]()
    4. [requests](https://requests.readthedocs.io/en/master/) - 轻量级爬虫框架，功能全面，不支持异步。
    5. [aiohttp](https://docs.aiohttp.org/en/stable/) - 异步爬虫框架，性能好。
    6. [httpx](https://www.python-httpx.org/) - 异步爬虫框架，性能好, 同步异步都支持。 [推荐: 适合需要灵活的爬虫]()
    7. [crawlab](https://github.com/crawlab-team/crawlab.git) - 分布式爬虫管理平台，功能全，部分功能需要收费/年。
    8. [Gerapy](https://github.com/Gerapy/Gerapy.git) - 分布式爬虫管理平台，功能全，但是文档不全,社区不活跃，作者属于半年或者几年维护一次的状态。[注: 每几个月出现bug导致任务无法按时运行]()
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
  - #### 数据库
    1. [SQLAlchemy](https://www.sqlalchemy.org/) - ORM 框架，功能全。
    2. [sqlmodel](https://github.com/tiangolo/sqlmodel.git) - Python 中的 SQL 数据库，旨在实现简单性、兼容性和稳健性。[推荐: 使用]()
    3. [pymongo](https://github.com/mongodb/mongo-python-driver.git) - MongoDB 底层级操作框架，功能全。
    4. [motor](https://github.com/mongodb/motor.git) - MongoDB 异步操作框架，性能好。
    5. [odmantic](https://github.com/art049/odmantic.git) - MongoDB ORM 框架与fastapi 绝配，但是作者处理bug问题不积极。
  - #### AI
    1. [langchain]() - AI LLM 底层级框架，灵活，提供丰富的功能。
    2. [llama_index]() - 基于 langchain 封装的数据索引 [推荐使用]()
    3. [guardrails](https://github.com/ShreyaR/guardrails.git) - AI LLM 为大型语言模型添加护栏。
    4. [chainlit](https://github.com/Chainlit/chainlit.git) - 在几分钟内构建Python LLM应用程序 [推荐使用]()
    5. [scikit-learn](https://scikit-learn.org/stable/) - 机器学习框架。
    6. [pytorch](https://pytorch.org/) - 深度学习框架。[推荐: 使用]()
    7. [tensorflow](https://www.tensorflow.org/) - 深度学习框架，功能全。
    8. [keras](https://keras.io/) - 深度学习框架。
    9. [xgboost](https://xgboost.readthedocs.io/en/latest/) - 机器学习框架。
    10. [lightgbm](https://lightgbm.readthedocs.io/en/latest/) - 机器学习框架。
    11. [catboost](https://catboost.ai/) - 机器学习框架。
  - #### 金融
    1. [akshare](https://github.com/akfamily/akshare.git) - 开源财经数据接口库。
    2. [backtrader](https://github.com/mementum/backtrader.git) - 开源量化交易框架。
  - #### 其他库
    1. [typer](https://github.com/tiangolo/typer.git) - 命令行框架，功能全 [推荐: 使用]()
    2. [ItChat-UOS](https://github.com/why2lyj/ItChat-UOS.git) - 基于 itchat 的微信机器人，支持多账号，多进程，多线程，多群聊，多好友，多消息类型，多消息格式，多终端（包括 Linux 终端）。
    3. [Asyncer](https://github.com/tiangolo/asyncer.git) - Asyncer，async and await，专注于开发者体验, 提升新能。[推荐: 使用]()
  - #### 项目
    1. [qinglong](https://github.com/whyour/qinglong.git) - 支持 Python3、JavaScript、Shell、Typescript 的定时任务管理平台（Timed task management platform supporting Python3, JavaScript, Shell, Typescript）
   
- ### [JS&TS]()
  - #### web
    1. [nestjs](https://github.com/nestjs/nest.git) - 重量级 web 框架集成很多功能开箱即用。
    2. [express](https://github.com/expressjs/express.git) - 底层级 web 框架，灵活。
  - #### 爬虫
    1. [crawlee](https://github.com/apify/crawlee.git) - 重量级 web 框架集成很多功能开箱即用。
    2. [apify-sdk](https://github.com/apify/apify-sdk-js.git) - 基于crawlee 爬虫管理平台有一定的免费空间。