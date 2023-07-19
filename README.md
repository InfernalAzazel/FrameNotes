## 框架笔记

### 编程语言
- ### [Python]()
  - #### 效率工具
    1. [poetry](https://python-poetry.org/) - Python 项目管理工具，类似于 npm。
    2. [pyenv](https://github.com/pyenv/pyenv.git) - Python 版本管理工具，类似于 nvm。   
  - #### web
    1. [Django](https://www.djangoproject.com/) - 重量级 web 框架集成很多功能开箱即用，缺点不灵活。
    2. [Flask](https://flask.palletsprojects.com/en/1.1.x/) - 轻量级 web 框架，灵活，但是需要自己实现很多功能。
    3. [Tornado](https://www.tornadoweb.org/en/stable/) - 异步 web 框架，性能好。
    4. [Sanic](https://sanic.readthedocs.io/en/latest/) - 异步 web 框架，性能好，但是文档不全，社区不活跃。
    5. [FastAPI](https://fastapi.tiangolo.com/) - 异步 web 框架，性能好，文档全，社区活跃，但是功能不全，需要自己实现很多功能。[推荐: 挺好用, 效率高，性能高， 简洁]()
  - #### 爬虫
    1. [Scrapy](https://scrapy.org/) - 重量级爬虫框架，功能全。[目前: 在使用]()
    2. [requests](https://requests.readthedocs.io/en/master/) - 轻量级爬虫框架，功能全面，不支持异步。
    3. [aiohttp](https://docs.aiohttp.org/en/stable/) - 异步爬虫框架，性能好。
    4. [httpx](https://www.python-httpx.org/) - 异步爬虫框架，性能好, 同步异步都支持。 [推荐: 适合需要灵活的爬虫]()
    5. [crawlab](https://github.com/crawlab-team/crawlab.git) - 分布式爬虫管理平台，功能全，部分功能需要收费/年。
    6. [Gerapy](https://github.com/Gerapy/Gerapy.git) - 分布式爬虫管理平台，功能全，但是文档不全,社区不活跃，作者属于半年或者几年维护一次的状态。[注: 每几个月出现bug导致任务无法按时运行]()
    7. [lxml](https://lxml.de/) – C语言编写高效HTML/XML处理库。支持XPath。
    8. [cssselect](https://cssselect.readthedocs.io/) – 解析DOM树和CSS选择器。
    9. [pyquery](https://pythonhosted.org/pyquery/) – 解析DOM树和jQuery选择器。
    10. [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/) – 低效HTML/XML处理库，纯Python实现。
    11. [html5lib](https://html5lib.readthedocs.io/) – 根据WHATWG规范生成HTML/XML文档的DOM。该规范被用在现在所有的浏览器上。
    12. [feedparser](https://pythonhosted.org/feedparser/) – 解析RSS/ATOM feeds。
    13. [MarkupSafe](https://palletsprojects.com/p/markupsafe/) – 为XML/HTML/XHTML提供了安全转义的字符串。
    14. [xmltodict](https://github.com/martinblech/xmltodict) – 一个可以让你在处理XML时感觉像在处理JSON一样的Python模块。
    15. [xhtml2pdf](https://github.com/xhtml2pdf/xhtml2pdf) – 将HTML/CSS转换为PDF。
    16. [untangle](https://github.com/stchris/untangle) – 轻松实现将XML文件转换为Python对象。
  - #### 定时任务 + 分布式
    1. [APScheduler](https://apscheduler.readthedocs.io/en/stable/) - 轻量级定时任务框架，功能全。[符合业务需求的推荐使用]()
    2. [Celery](https://docs.celeryproject.org/en/stable/) - 重量级定时任务框架，功能全。 [注: 长期运行的任务支持差]()
    3. [Ray](https://docs.ray.io/en/latest/) - AI 分布式任务训练框架，高性能，功能全。[推荐: 使用]()
  - #### 数据处理
    1. [pydantic](https://pydantic-docs.helpmanual.io/) - 数据校验框架，功能全。[推荐: 使用]()
    2. [lux](https://github.com/lux-org/lux.git) - 简单地在 Jupyter 笔记本中打印出数据框，Pandas 配合Lux 输出可视化效果图表
    3. [pandas](https://pandas.pydata.org/) - 数据分析框架。[目前:常用, 处理 excel csv 非常方便]()
    4. [numpy](https://numpy.org/) - 数学计算框架。
    5. [scipy](https://www.scipy.org/) - 科学计算框架。
    6. [matplotlib](https://matplotlib.org/) - 数据可视化框架。
    7. [seaborn](https://seaborn.pydata.org/) - 数据可视化框架。
    8. [difflib](https://docs.python.org/3/library/difflib.html) – （Python标准库）帮助进行差异化比较。
    9. [Levenshtein](https://pypi.org/project/python-Levenshtein/) – 快速计算Levenshtein距离和字符串相似度。
    10. [fuzzywuzzy](https://pypi.org/project/fuzzywuzzy/) – 模糊字符串匹配。
    11. [esmre](https://pypi.org/project/esmre/) – 正则表达式加速器。
    12. [ftfy](https://pypi.org/project/ftfy/) – 自动整理Unicode文本，减少碎片化。
  - #### 数据库
    1. [SQLAlchemy](https://www.sqlalchemy.org/) - ORM 框架，功能全。
    2. [sqlmodel](https://github.com/tiangolo/sqlmodel.git) - Python 中的 SQL 数据库，旨在实现简单性、兼容性和稳健性
    3. [pymongo](https://github.com/mongodb/mongo-python-driver.git) - MongoDB 底层级操作框架，功能全。 。[推荐: 使用]()
    4. [motor](https://github.com/mongodb/motor.git) - MongoDB 异步操作框架，性能好。 。[推荐: 使用]()
    5. [odmantic](https://github.com/art049/odmantic.git) - MongoDB ORM 框架与fastapi 绝配，但是作者处理bug问题不积极。
    6. [beanie](https://github.com/roman-right/beanie.git) - MongoDB ORM 框架, 基于 motor 开发能与 fastapi配合
  - #### AI
    1. [langchain]() - AI LLM 底层级框架，灵活，提供丰富的功能。
    2. [llama_index]() - 基于 langchain 封装的数据索引 [推荐使用]()
    3. [guardrails](https://github.com/ShreyaR/guardrails.git) - AI LLM 为大型语言模型添加护栏。
    4. [chainlit](https://github.com/Chainlit/chainlit.git) - 在几分钟内构建Python LLM应用程序 [推荐使用]()
    5. [scikit-learn](https://scikit-learn.org/stable/) - 机器学习框架。
    6. [pytorch](https://pytorch.org/) - 深度学习框架。[推荐: 使用]()
    7. [lightning](https://www.pytorchlightning.ai/) - 基于 pytorch 封装简化开发，实现工程于科学分离的框架 [推荐: 使用]()
    8. [tensorflow](https://www.tensorflow.org/) - 深度学习框架，功能全。
    9. [keras](https://keras.io/) - 深度学习框架。
    10. [xgboost](https://xgboost.readthedocs.io/en/latest/) - 机器学习框架。
    11. [lightgbm](https://lightgbm.readthedocs.io/en/latest/) - 机器学习框架。
    12. [catboost](https://catboost.ai/) - 机器学习框架。
  - #### 金融
    1. [akshare](https://github.com/akfamily/akshare.git) - 开源财经数据接口库。
    2. [backtrader](https://github.com/mementum/backtrader.git) - 开源量化交易框架。
  - #### 其他库
    1. [typer](https://github.com/tiangolo/typer.git) - 命令行框架，功能全 [推荐: 使用]()
    2. [ItChat-UOS](https://github.com/why2lyj/ItChat-UOS.git) - 基于 itchat 的微信机器人，支持多账号，多进程，多线程，多群聊，多好友，多消息类型，多消息格式，多终端（包括 Linux 终端）。
    3. [Asyncer](https://github.com/tiangolo/asyncer.git) - Asyncer，async and await，专注于开发者体验, 提升新能。[推荐: 使用]()
    4. [tenacity](https://github.com/jd/tenacity) - 重试框架，功能全 比如使用于 http 请求超时重新执行函数。
    5. [memray](https://github.com/bloomberg/memray.git) - 内存分析工具, 使用场景 1.优化内存使用 2.调试内存泄漏 3.分析对象引用。
    6. [pytest](https://github.com/pytest-dev/pytest.git) - 测试框架，该库可以支持应用程序和库的简单与复杂功能测试。
    7. [loguru](https://github.com/Delgan/loguru.git) - 日志框架，该库旨在通过添加一系列有用的功能来解决标准log的警告，从而减少 Python 日志记录的繁琐步骤。
    8. [mypy](https://github.com/python/mypy.git) - 静态类型检查器，该库可以帮助开发者在开发过程中发现代码中的错误。
  - #### 项目
    1. [qinglong](https://github.com/whyour/qinglong.git) - 支持 Python3、JavaScript、Shell、Typescript 的定时任务管理平台
    2. [minio](https://github.com/minio/minio-py.git) - MinIO OSS 云储存支持群集 [推荐: 使用]()
   
- ### [JS&TS]()
  - #### web
    1. [nestjs](https://github.com/nestjs/nest.git) - 重量级 web 框架集成很多功能开箱即用。
    2. [express](https://github.com/expressjs/express.git) - 底层级 web 框架，灵活。
  - #### 爬虫
    1. [crawlee](https://github.com/apify/crawlee.git) - 重量级 web 框架集成很多功能开箱即用。
    2. [apify-sdk](https://github.com/apify/apify-sdk-js.git) - 基于crawlee 爬虫管理平台有一定的免费空间。