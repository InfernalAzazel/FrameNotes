## 框架笔记

### 编程语言
- ### [Python]()
  - #### 效率工具
    1. [poetry](https://python-poetry.org/) - Python 项目管理工具，类似于 npm。
    2. [pyenv](https://github.com/pyenv/pyenv.git) - Python 版本管理工具，类似于 nvm。  
    3. [Dynaconf](https://github.com/dynaconf/dynaconf) - Python 的配置管理
    4. [pytest](https://github.com/pytest-dev/pytest) - pytest框架可以轻松编写小型、可读的测试，并且可以扩展以支持应用程序和库的复杂功能测试。
    5. [python-dotenv](https://github.com/theskumar/python-dotenv)- python-dotenv 从文件中读取键值对.env，并可以将它们设置为环境变量
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
    17. [dominate](https://github.com/Knio/dominate) - 在 python 代码上轻松写 html 内容 [推荐: 好用]()
  - #### 定时任务 + 分布式
    1. [APScheduler](https://apscheduler.readthedocs.io/en/stable/) - 轻量级定时任务框架，功能全。[符合业务需求的推荐使用]()
    2. [Celery](https://docs.celeryproject.org/en/stable/) - 重量级定时任务框架，功能全。 [注: 功能强大，要求细节处理]()
    3. [Ray](https://docs.ray.io/en/latest/) - AI 分布式任务训练框架，高性能，功能全。
    4. [rq](https://python-rq.org/) - celery 的代替品轻量级框架 [强烈推荐]()
  - #### 数据处理
    1. [pydantic](https://pydantic-docs.helpmanual.io/) - 数据校验框架，功能全。[推荐: 使用]()
    2. [pydantic_extra_types](https://github.com/pydantic/pydantic-extra-types) - pydantic 扩展额外数据类型
    3. [pydantic-settings](https://github.com/pydantic/pydantic-settings) -  pydantic 扩展可获取环境变量
    4. [lux](https://github.com/lux-org/lux.git) - 简单地在 Jupyter 笔记本中打印出数据框，Pandas 配合Lux 输出可视化效果图表
    5. [pandas](https://pandas.pydata.org/) - 数据分析框架。[目前:常用, 处理 excel csv 非常方便]()
    6. [numpy](https://numpy.org/) - 数学计算框架。
    7. [scipy](https://www.scipy.org/) - 科学计算框架。
    8. [matplotlib](https://matplotlib.org/) - 数据可视化框架。
    9. [seaborn](https://seaborn.pydata.org/) - 数据可视化框架。
    10. [difflib](https://docs.python.org/3/library/difflib.html) – （Python标准库）帮助进行差异化比较。
    11. [Levenshtein](https://pypi.org/project/python-Levenshtein/) – 快速计算Levenshtein距离和字符串相似度。
    12. [fuzzywuzzy](https://pypi.org/project/fuzzywuzzy/) – 模糊字符串匹配。
    13. [esmre](https://pypi.org/project/esmre/) – 正则表达式加速器。
    14. [ftfy](https://pypi.org/project/ftfy/) – 自动整理Unicode文本，减少碎片化。
    15. [ansi2html](https://github.com/pycontribs/ansi2html) - 将终端输出高亮文本转换为html高亮 [注: 好用]()
    16. [weasyprint](https://github.com/Kozea/WeasyPrint) - 将 html 完美 转成 PDF  [注: 神器]()
    17. [pygments](https://github.com/pygments/pygments) - 代码高亮 [注: 神器]()
    18. [rich](https://github.com/Textualize/rich) - 打造令人愉悦的命令行界面。
    19. [tqdm](https://github.com/tqdm/tqdm) - 显示进度条的模块,可迭代对象和CLI中使用。
    20. [Pillow](https://github.com/python-pillow/Pillow) - Pillow图像处理库。
  - #### 图形界面库
    1. [DearPyGui](https://github.com/hoffstadt/DearPyGui.git) - 跨平台图形界面库，功能全
    2. [nicegui](https://github.com/zauberzeug/nicegui.git) - 跨平台图形界面库
    3. [qt-material](https://github.com/UN-GCPDS/qt-material.git) - 跨平台图形界面主题库
  - #### 网络编程
    1. [Twisted](https://github.com/twisted/twisted) - 是一个异步网络框架,可以用它来建立远程桌面连接,传输画面等。
    2. [Impacket](https://github.com/fortra/impacket) - Impacket是一个用于处理网络协议的Python库，旨在为渗透测试人员、网络安全研究人员和开发人员提供一种方便的方式来与网络协议进行交互。它提供了许多用于处理和操作各种网络协议的功能和工具.
    3. [Paramiko](https://github.com/paramiko/paramiko) - 一个用于SSH和SFTP的Python实现，可用于通过SSH协议进行远程命令执行和文件传输。
    4. [pycryptodomex](https://github.com/Legrandin/pycryptodome) - PyCryptodome 是一个独立的 Python 低级加密原语包。
    5. [cryptography](https://github.com/pyca/cryptography) - 是一个为 Python 开发人员提供加密配方和原语的包。我们的目标是让它成为您的“密码标准库”。
    6. [Scapy](https://github.com/secdev/scapy) - 一个功能强大的网络包操作工具和交互库，可以用于创建、发送和解析网络数据包。它可以用于网络扫描、漏洞利用、协议分析等任务。
    7. [python3-nmap](https://github.com/nmmapper/python3-nmap) - 与Nmap（网络映射器）工具进行集成的库，用于进行端口扫描和服务识别。它可以用于发现目标主机上开放的端口和运行的服务。
  - #### 数据库
    1. [SQLAlchemy](https://www.sqlalchemy.org/) - ORM 框架，功能全。
    2. [sqlmodel](https://github.com/tiangolo/sqlmodel.git) - Python 中的 SQL 数据库，旨在实现简单性、兼容性和稳健性
    3. [pymongo](https://github.com/mongodb/mongo-python-driver.git) - MongoDB 底层级操作框架，功能全。
    4. [motor](https://github.com/mongodb/motor.git) - MongoDB 异步操作框架，性能好。
    5. [odmantic](https://github.com/art049/odmantic.git) - MongoDB ORM 框架与fastapi 绝配，但是作者处理bug问题不积极。
    6. [beanie](https://github.com/roman-right/beanie.git) - MongoDB ORM 框架, 基于 motor 开发能与 fastapi配合 [推荐: 使用]()
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
    13. [text2vec](https://github.com/InfernalAzazel/text2vec.git) - 文本向量化框架，功能全。
    14. [modelscope](https://github.com/modelscope/modelscope.git) - 模型可视化框架，功能全。
    15. [transformers](https://github.com/huggingface/transformers.git) - 自然语言处理框架，功能全。
    16. [spaCy](https://github.com/explosion/spaCy.git) - 分词框架，功能全。
  - #### 金融
    1. [akshare](https://github.com/akfamily/akshare.git) - 开源财经数据接口库。
    2. [backtrader](https://github.com/mementum/backtrader.git) - 开源量化交易框架。
    3. [fastquant](https://github.com/enzoampil/fastquant.git) - 开源量化交易框架。
    4. [tqsdk-python](https://github.com/shinnytech/tqsdk-python) - 开源量化交易框架, 可以实盘操作。
  - #### 其他库
    1. [typer](https://github.com/tiangolo/typer.git) - 命令行框架，功能全 [推荐: 使用]()
    2. [ItChat-UOS](https://github.com/why2lyj/ItChat-UOS.git) - 基于 itchat 的微信机器人，支持多账号，多进程，多线程，多群聊，多好友，多消息类型，多消息格式，多终端（包括 Linux 终端）。
    3. [Asyncer](https://github.com/tiangolo/asyncer.git) - Asyncer，async and await，专注于开发者体验, 提升新能。[推荐: 使用]()
    4. [tenacity](https://github.com/jd/tenacity) - 重试框架，功能全 比如使用于 http 请求超时重新执行函数。
    5. [memray](https://github.com/bloomberg/memray.git) - 内存分析工具, 使用场景 1.优化内存使用 2.调试内存泄漏 3.分析对象引用。
    6. [loguru](https://github.com/Delgan/loguru.git) - 日志框架，该库旨在通过添加一系列有用的功能来解决标准log的警告，从而减少 Python 日志记录的繁琐步骤。
    7. [structlog](https://github.com/hynek/structlog.git) - structlog是Python 的生产就绪日志记录解决方案, 简单 功能强大 快速
    8. [mypy](https://github.com/python/mypy.git) - 静态类型检查器，该库可以帮助开发者在开发过程中发现代码中的错误。
    9. [weblate]() - 协作翻译平台，支持自部署。
    10. [googlesearch](https://github.com/Nv7-GitHub/googlesearch.git) - 谷歌搜索接口，支持自定义搜索引擎。
    11. [arrow](https://arrow.readthedocs.io/en/latest/) - Arrow是一个 Python 库，它提供了一种合理且人性化的方法来创建、操作、格式化和转换日期、时间和时间戳。它实现并更新了日期时间类型，填补了功能空白并提供了支持许多常见创建场景的智能模块 API。简而言之，它可以帮助您使用更少的导入和更少的代码来处理日期和时间。
  - #### 项目
    1. [qinglong](https://github.com/whyour/qinglong.git) - 支持 Python3、JavaScript、Shell、Typescript 的定时任务管理平台
    2. [minio](https://github.com/minio/minio-py.git) - MinIO OSS 云储存支持群集 [推荐: 使用]()
    3. [electerm](https://github.com/electerm/electerm.git) - 一个跨平台的终端/远程管理器，支持 Linux、MacOS、Windows
    4. [Auto-GPT](https://github.com/Significant-Gravitas/Auto-GPT.git) - 一个自动化的 GPT-3 生成器。
    5. [stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui.git) - 一个图片生成 AI项目。
    6. [vnpy](https://github.com/vnpy/vnpy.git) - 一个开源量化交易平台。
    7. [urh](https://github.com/jopohl/urh.git) - 一个开源无线电分析和攻击工具。
    8. [mirai](https://github.com/mamoe/mirai.git) - 一个开源 QQ 机器人框架。