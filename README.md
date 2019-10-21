# Pypackage
python package

### Python package
```
* Requests：Kenneth Reitz写的最富盛名的http库。每个Python程序员都应该有它。
* Scrapy：如果你从事爬虫相关的工作，那么这个库也是必不可少的。用过它之后你就不会再想用别的同类库了。
* wxPython：Python的一个GUI（图形用户界面）工具。我主要用它替代tkinter。你一定会爱上它的。
* Pillow：它是PIL（Python图形库）的一个友好分支。对于用户比PIL更加友好，对于任何在图形领域工作的人是必备的库。
* SQLAlchemy：一个数据库的库。对它的评价褒贬参半。是否使用的决定权在你手里。
* BeautifulSoup：我知道它很慢，但这个xml和html的解析库对于新手非常有用。
* Twisted：对于网络应用开发者最重要的工具。它有非常优美的api，被很多Python开发大牛使用。
* NumPy：我们怎么能缺少这么重要的库？它为Python提供了很多高级的数学方法。
* SciPy：既然我们提了NumPy，那就不得不提一下SciPy。这是一个Python的算法和数学工具库，它的功能把很多科学家从Ruby吸引到了Python。
* matplotlib：一个绘制数据图的库。对于数据科学家或分析师非常有用。
* Pygame：哪个程序员不喜欢玩游戏和写游戏？这个库会让你在开发2D游戏的时候如虎添翼。
* Pyglet：3D动画和游戏开发引擎。非常有名的Python版本Minecraft就是用这个引擎做的。
* pyQT：Python的GUI工具。这是我在给Python脚本开发用户界面时次于wxPython的选择。
* pyGtk：也是Python GUI库。很有名的Bittorrent客户端就是用它做的。
* Scapy：用Python写的数据包探测和分析库。
* pywin32：一个提供和windows交互的方法和类的Python库。
* nltk：自然语言工具包。我知道大多数人不会用它，但它通用性非常高。如果你需要处理字符串的话，它是非常好的库。但它的功能远远不止如此，自己摸索一下吧。
* nose：Python的测试框架。被成千上万的Python程序员使用。如果你做测试导向的开发，那么它是必不可少的。
* SymPy：SymPy可以做代数评测、差异化、扩展、复数等等。它封装在一个纯Python发行版本里。
* IPython：怎么称赞这个工具的功能都不为过。它把Python的提示信息做到了极致。包括完成信息、历史信息、shell功能，以及其他很多很多方面。一定要研究一下它。
* psutil：一个跨平台库能够实现获取系统运行的进程和系统利用率（内存，CPU,磁盘，网络等），主要用于系统监控，分析和系统资源及进程的管理。
* IPy：辅助IP规划。
* dnspython：DNS工具包。
* difflib：Python的标准模块，无需安装，作用是对比文本之间的差异。
* filecmp:系统自带，可以实现文件，目录，遍历子目录的差异，对比功能。
* smtplib：发送电子邮件模块
* pycurl：用C语言写的libcurl Python实现，功能强大，支持的协议有：FTP,HTTP,HTTPS,TELNET等，可以理解为Linux下curl命令功能的Python封装。
* XlsxWriter：操作Excel工作表的文字，数字，公式，图表等。
* rrdtool:用于跟踪对象的变化，生成这些变化的走走势图
* scapy：强大的交互式数据包处理程序，它能够对数据包进行伪造或解包，包括发送数据包，包嗅探，应答和反馈等功能。
* Clam Antivirus：免费开放源代码防毒软件，pyClamad,可以让Python模块直接使用ClamAV病毒扫描守护进程calmd。
* pexpect:可以理解成Linux下expect的Python封装，通过pexpect我们可以实现对ssh,ftp,passwd,telnet等命令行进行自动交互，而无需人工干涉来达到自动化的目的。
* paramiko：基于Python实现的SSH2远程安装连接，支持认证及密钥方式。可以实现远程命令执行，文件传输，中间SSH代理等功能。相对于Pexpect,封装的层次更高，更贴近SSH协议的功能
* fabric：基于Python实现的SSH命令行工具，简化了SSH的应用程序部署及系统管理任务，它提供了系统基础的操作组件，可以实现本地或远程shell命令，包括命令执行，文件上传，下载及完整执行日志输出等功能。Fabric在paramiko的基础上做了更高一层的封装，操作起来更加简单。
* ansible：集成IT系统的配置管理，应用部署，执行特定任务的开源平台。基于Python实现，由Paramiko和PyYAML两个关键模块构建。Ansibl与Saltstack最大的区别是Ansible无需在被控主机上部署任何客户端，默认直接通过SSH通道进行远程命令执行或下发功能。
* YAML:是一种用来表达数据序列的编程语言。
* playbook：一个非常简单的配置管理和多主机部署系统。
* saltstack：服务器基础架构集中化管理平台，一般可以理解为简化版的puppet和加强版的func。Saltstack基于Python语言实现，结合轻量级消息队列ZeroMQ,与Python每三方模块（Pyzmq,PyCrypto,Pyjinja2,python-msgpack和PyYAML等）构建。
* func：为解决集群管理，监控问题需设计开发的系统管理基础框架。
* re：正则
* subprocess：调用shell命令的神器
* pdb：调试
* traceback：调试
* pprint：漂亮的输出
* logging：日志
* threading和multiprocessing：多线程
urllib/urllib2/httplib http库：httplib底层一点，推荐第三方的库requests
* os/sys：系统，环境相关
* Queue：队列
* pickle/cPickle：序列化工具
* hashlib：md5, sha等hash算法
* cvs：json/simplejson python的json库，据so上的讨论和benchmark，simplejson的性能要高于json
* time：it 计算代码运行的时间等等
* cProfile：python性能测量模块
* glob：类似与listfile，可以用来查找文件
* atexit：注册函数，可用于正好在脚本退出运行前执行一些代码
* dis：python 反汇编，当对某条语句不理解原理时，可以用dis.dis 函数来查看代码对应的python 解释器指令等等。
* paramiko:ssh python 库
* selenium：浏览器自动化测试工具selenium的python 接口
* lxml：python 解析html,xml 的神器
* mechanize： Stateful programmatic web browsing
* pycurl：cURL library module for Python
* xmltodict：xml 转 dict，真心好用
* urllib3 和 requests: 当然其实requests就够了 Requests: HTTP for Humans
* flask： web 微框架
* ipdb：调试神器，同时推荐ipython！结合ipython使用
* redis：redis python接口
* pymongo：mongodb python接口
* PIL： python图像处理
* mako：python模版引擎
* numpy：scipy 科学计算
* matplotlib：画图
* scrapy：爬虫
* cherrypy：python web框架/服务器
* sh：用来运行shell 模块的 极佳选择
* p：非常简单的交互式 python 版本管理工具。
* pyenv：简单的 Python 版本管理工具。
* Vex：可以在虚拟环境中执行命令。
* virtualenv： 创建独立 Python 环境的工具。
* virtualenvwrapper：virtualenv 的一组扩展。
* pip：Python 包和依赖关系管理工具。
* pip-tools： Python 包依赖关系更新的一组工具。
* conda ：跨平台，Python 二进制包管理工具。
* Curdling ：管理 Python 包的命令行工具。
* wheel：Python 分发的新标准，意在取代 eggs。
* warehouse：下一代 PyPI。
* Warehousebandersnatch ：PyPA 提供的 PyPI 镜像工具。
* devpi：PyPI 服务和打包/测试/分发工具。
* localshop ：本地 PyPI 服务（自定义包并且自动对 PyPI 镜像）。
* PyInstaller：将 Python 程序转换成独立的执行文件（跨平台）。
* dh-virtualenv：构建并将 virtualenv 虚拟环境作为一个 Debian 包来发布。
* Nuitka：将脚本、模块、包编译成可执行文件或扩展模块。
* py2app：将 Python 脚本变为独立软件包（Mac OS X）。
* py2exe：将 Python 脚本变为独立软件包（Windows）。
* pynsist：一个用来创建 Windows 安装程序的工具，可以在安装程序中打包 Python本身。
* buildout：一个构建系统，从多个组件来创建，组装和部署应用。
* BitBake：针对嵌入式 Linux 的类似 make 的构建工具。
* fabricate：对任何语言自动找到依赖关系的构建工具。
* PlatformIO：多平台命令行构建工具。
* PyBuilder：纯 Python 实现的持续化构建工具。
* SCons：软件构建工具。
* IPython：功能丰富的工具，非常有效的使用交互式 Python。
* bpython：界面丰富的 Python 解析器。
* ptpython：高级交互式Python解析器， 构建于python-prompt-toolkit 之上。
* imghdr：（Python 标准库）检测图片类型。
* mimetypes：（Python 标准库）将文件名映射为 MIME 类型。
* path.py：对 os.path 进行封装的模块。
* pathlib：（Python3.4+ 标准库）跨平台的、面向对象的路径操作库。
* python-magic：文件类型检测的第三方库 libmagic 的 Python 接口。
* Unipath：用面向对象的方式操作文件和目录
* watchdog：管理文件系统事件的 API 和 shell 工具
* sarrow- 更好的 Python 日期时间操作类库。
* Chronyk：Python 3 的类库，用于解析手写格式的时间和日期。
* dateutil：Python datetime 模块的扩展。
* delorean：解决 Python 中有关日期处理的棘手问题的库。
* moment：一个用来处理时间和日期的Python库。灵感来自于Moment.js。
* PyTime：一个简单易用的Python模块，用于通过字符串来操作日期/时间。
* pytz：现代以及历史版本的世界时区定义。将时区数据库引入Python。
* when.py：提供用户友好的函数来帮助用户进行常用的日期和时间操作。
* chardet：字符编码检测器，兼容 Python2 和 Python3。
* difflib：(Python 标准库)帮助我们进行差异化比较。
* ftfy：让Unicode文本更完整更连贯。
* fuzzywuzzy：模糊字符串匹配。
* Levenshtein：快速计算编辑距离以及字符串的相似度。
* pangu.py：在中日韩语字符和数字字母之间添加空格。
* pyfiglet：figlet 的 Python实现。
* shortuuid：一个生成器库，用以生成简洁的，明白的，URL 安全的 UUID。
* unidecode：Unicode 文本的 ASCII 转换形式 。
* uniout：打印可读的字符，而不是转义的字符串。
* xpinyin：一个用于把汉字转换为拼音的库。
* awesome-slugify：一个 Python slug 化库，可以保持 Unicode。
* python-slugify：Python slug 化库，可以把 unicode 转化为 ASCII。
* unicode-slugify：一个 slug 工具，可以生成 unicode slugs ,需要依赖 Django 。
* phonenumbers：解析，格式化，储存，验证电话号码。
* PLY：lex 和 yacc 解析工具的 Python 实现。
* Pygments：通用语法高亮工具。
* pyparsing：生成通用解析器的框架。
* python-nameparser：把一个人名分解为几个独立的部分。
* python-user-agents：浏览器 user agent 解析器。
* sqlparse：一个无验证的 SQL 解析器。
* tablib：一个用来处理中表格数据的模块。
* Marmir：把输入的Python 数据结构转换为电子表单。
* openpyxl：一个用来读写 Excel 2010 xlsx/xlsm/xltx/xltm 文件的库。
* python-docx：读取，查询以及修改 Microsoft Word 2007/2008 docx 文件。
* unoconv：在 LibreOffice/OpenOffice 支持的任意文件格式之间进行转换。
* XlsxWriter：一个用于创建 Excel .xlsx 文件的 Python 模块。
* xlwings：一个使得在 Excel 中方便调用 Python 的库（反之亦然），基于 BSD 协议。
* xlwt/xlrd：读写 Excel 文件的数据和格式信息。
* relatorio：模板化OpenDocument 文件。
* PDFMiner：一个用于从PDF文档中抽取信息的工具。
* PyPDF2：一个可以分割，合并和转换 PDF 页面的库。
* ReportLab：快速创建富文本 PDF 文档。
Markdown
* Mistune：快速并且功能齐全的纯 Python 实现的 Markdown 解析器。
* Python-Markdown：John Gruber’s Markdown 的 Python 版实现。
* PyYAML：Python 版本的 YAML 解析器。
* csvkit：用于转换和操作 CSV 的工具。
* unp：一个用来方便解包归档文件的命令行工具。
* NLTK：一个先进的平台，用以构建处理人类语言数据的 Python 程序。
* jieba：中文分词工具。
* langid.py：独立的语言识别系统。
* Pattern：Python 网络信息挖掘模块。
* SnowNLP：一个用来处理中文文本的库。
* TextBlob：为进行普通自然语言处理任务提供一致的 API。
* TextGrocery：一简单高效的短文本分类工具，基于 LibLinear 和 Jieba。
* Sphinx：Python 文档生成器。
awesome-sphinxdoc
* MkDocs：对 Markdown 友好的文档生成器。
* pdoc：一个可以替换Epydoc 的库，可以自动生成 Python 库的 API 文档。
* Pycco：文学编程（literate-programming）风格的文档生成器。
* config：logging 模块作者写的分级配置模块。
* ConfigObj：INI 文件解析器，带验证功能。
* ConfigParser：(Python 标准库) INI 文件解析器。
* profig：通过多种格式进行配置，具有数值转换功能。
* python-decouple：将设置和代码完全隔离。
* cement：Python 的命令行程序框架。
* click：一个通过组合的方式来创建精美命令行界面的包。
* cliff：一个用于创建命令行程序的框架，可以创建具有多层命令的命令行程序。
* clint：Python 命令行程序工具。
* colorama：跨平台彩色终端文本。
* docopt：Python 风格的命令行参数解析器。
* Gooey：一条命令，将命令行程序变成一个 GUI 程序。
* python-prompt-toolkit：一个用于构建强大的交互式命令行程序的库。
* aws-cli：Amazon Web Services 的通用命令行界面。
* bashplotlib：在终端中进行基本绘图。
* caniusepython3：判断是哪个项目妨碍你你移植到 Python 3。
* cookiecutter：从 cookiecutters（项目模板）创建项目的一个命令行工具。
* doitlive：一个用来在终端中进行现场演示的工具。
* howdoi：通过命令行获取即时的编程问题解答。
* httpie：一个命令行HTTP 客户端，cURL 的替代品，易用性更好。
* PathPicker：从bash输出中选出文件。
* percol：向UNIX shell 传统管道概念中加入交互式选择功能。
* SAWS：一个加强版的 AWS 命令行。
* thefuck：修正你之前的命令行指令。
* mycli：一个 MySQL 命令行客户端，具有自动补全和语法高亮功能。
* pgcli：Postgres 命令行工具，具有自动补全和语法高亮功能。
* s3cmd：一个用来管理Amazon S3 和 CloudFront 的命令行工具。
* s4cmd：超级 S3 命令行工具，性能更加强劲。
* you-get：一个 YouTube/Youku/Niconico 视频下载器，使用 Python3 编写。
* youtube-dl：一个小巧的命令行程序，用来下载 YouTube 视频。
* pillow：Pillow 是一个更加易用版的 PIL。
* hmap：图像直方图映射。
* imgSeek：一个使用视觉相似性搜索一组图片集合的项目。
* nude.py：裸体检测。
* pyBarcode：不借助 PIL 库在 Python 程序中生成条形码。
* pygram：类似 Instagram 的图像滤镜。
* python-qrcode：一个纯 Python 实现的二维码生成器。
* Quads：基于四叉树的计算机艺术。
* scikit-image：一个用于（科学）图像处理的 Python 库。
* thumbor：一个小型图像服务，具有剪裁，尺寸重设和翻转功能。
* wand：MagickWand的Python 绑定。MagickWand 是 ImageMagick的 C API 。
* pyocr：Tesseract 和 Cuneiform 的一个封装(wrapper)。
* pytesseract：Google Tesseract OCR 的另一个封装(wrapper)。
* python-tesseract：Google Tesseract OCR 的一个包装类。
* audiolazy -Python 的数字信号处理包。
* audioread：交叉库 (GStreamer + Core Audio + MAD + FFmpeg) 音频解码。
* beets：一个音乐库管理工具及 MusicBrainz 标签添加工具
* dejavu：音频指纹提取和识别
* django-elastic-transcoder：Django + Amazon Elastic Transcoder。
* eyeD3：一个用来操作音频文件的工具，具体来讲就是包含 ID3 元信息的 MP3 文件。
* id3reader：一个用来读取 MP3 元数据的 Python 模块。
* m3u8：一个用来解析 m3u8 文件的模块。
* mutagen：一个用来处理音频元数据的 Python 模块。
* pydub：通过简单、简洁的高层接口来操作音频文件。
* pyechonest：Echo Nest API 的 Python 客户端
* talkbox：一个用来处理演讲/信号的 Python 库
* TimeSide：开源 web 音频处理框架。
* tinytag：一个用来读取MP3, OGG, FLAC 以及 Wave 文件音乐元数据的库。
* mingus：一个高级音乐理论和曲谱包，支持 MIDI 文件和回放功能。
* moviepy：一个用来进行基于脚本的视频编辑模块，适用于多种格式，包括动图 GIFs。
* scikit-video：SciPy 视频处理常用程序。
* GeoDjango：世界级地理图形 web 框架。
* GeoIP：MaxMind GeoIP Legacy 数据库的 Python API。
* geojson：GeoJSON 的 Python 绑定及工具。
* geopy：Python 地址编码工具箱。
* pygeoip：纯 Python GeoIP API。
* django-countries：一个 Django 应用程序，提供用于表格的国家选择功能，国旗图标静态文件以及模型中的国家字段。
* requests：人性化的HTTP请求库。
* grequests：requests 库 + gevent ，用于异步 HTTP 请求.
* httplib2：全面的 HTTP 客户端库。
* treq：类似 requests 的Python API 构建于 Twisted HTTP 客户端之上。
* urllib3：一个具有线程安全连接池，支持文件 post，清晰友好的 HTTP 库。
* pickleDB：一个简单，轻量级键值储存数据库。
* PipelineDB：流式 SQL 数据库。
* TinyDB：一个微型的，面向文档型数据库。
* ZODB：一个 Python 原生对象数据库。一个键值和对象图数据库。
* MySQL：awesome-mysql系列
* mysql-python：Python 的 MySQL 数据库连接器。
* mysqlclient：mysql-python 分支，支持 Python 3。
* oursql：一个更好的 MySQL 连接器，支持原生预编译指令和 BLOBs.
* PyMySQL：纯 Python MySQL 驱动，兼容 mysql-python。
PostgreSQL
* psycopg2：Python 中最流行的 PostgreSQL 适配器。
* queries：psycopg2 库的封装，用来和 PostgreSQL 进行交互。
* txpostgres：基于 Twisted 的异步 PostgreSQL 驱动。
* apsw：另一个 Python SQLite封装。
* dataset：在数据库中存储Python字典：可以协同SQLite，MySQL，和 PostgreSQL工作。
* pymssql- 一个简单的Microsoft SQL Server数据库接口。
* cassandra-python-driver：Cassandra 的 Python 驱动。
* HappyBase：一个为 Apache HBase 设计的，对开发者友好的库。
* Plyvel：一个快速且功能丰富的 LevelDB 的 Python 接口。
* py2neo：Neo4j restful 接口的Python 封装客户端。
* pycassa：Cassandra 的 Python Thrift 驱动。
* PyMongo：MongoDB 的官方 Python 客户端。
* redis-py：Redis 的 Python 客户端。
* telephus：基于 Twisted 的 Cassandra 客户端。
* txRedis：基于 Twisted 的 Redis 客户端。
* Django Models：Django 的一部分。
* SQLAlchemy：Python SQL 工具以及对象关系映射工具。
* awesome-sqlalchemy系列
* Peewee：一个小巧，富有表达力的 ORM。
* PonyORM：提供面向生成器的 SQL 接口的 ORM。
* python-sql：编写 Python 风格的 SQL 查询。
* django-mongodb-engine：Django MongoDB 后端。
* PynamoDB：Amazon DynamoDB 的一个 Python 风格接口。
* flywheel：Amazon DynamoDB 的对象映射工具。
* MongoEngine：一个Python 对象文档映射工具，用于 MongoDB。
* hot-redis：为 Redis 提供 Python 丰富的数据类型。
* redisco：一个 Python 库，提供可以持续存在在 Redis 中的简单模型和容器。
* butterdb：Google Drive 电子表格的 Python ORM。
* Django：Python 界最流行的 web 框架。
awesome-django系列
* Flask：一个 Python 微型框架。
* Pyramid：一个小巧，快速，接地气的开源Python web 框架。
* Bottle：一个快速小巧，轻量级的 WSGI 微型 web 框架。
* CherryPy：一个极简的 Python web 框架，服从 HTTP/1.1 协议且具有WSGI 线程池。
* TurboGears：一个可以扩展为全栈解决方案的微型框架。
* web.py：一个 Python 的 web 框架，既简单，又强大。
* web2py：一个全栈 web 框架和平台，专注于简单易用。
* Tornado：一个web 框架和异步网络库。
* django-guardian：Django 1.2+ 实现了单个对象权限。
* django-rules：一个小巧但是强大的应用，提供对象级别的权限管理，且不需要使用数据库。
* django-cms：一个开源的，企业级 CMS，基于 Django。
djedi-cms：一个轻量级但却非常强大的 Django CMS ，考虑到了插件，内联编辑以及性能。
* FeinCMS：基于 Django 构建的最先进的内容管理系统之一。
* Kotti：一个高级的，Python 范的 web 应用框架，基于 Pyramid 构建。
* Mezzanine：一个强大的，持续的，灵活的内容管理平台。
* Opps：一个为杂志，报纸网站以及大流量门户网站设计的 CMS 平台，基于 Django。
* Plone：一个构建于开源应用服务器 Zope 之上的 CMS。
* Quokka：灵活，可扩展的小型 CMS，基于 Flask 和 MongoDB。
* Wagtail：一个 Django 内容管理系统。
* Widgy：最新的 CMS 框架，基于 Django。
* django-oscar：一个用于 Django 的开源的电子商务框架。
* django-shop：一个基于 Django 的店铺系统。
* Cartridge：一个基于 Mezzanine 构建的购物车应用。
* shoop：一个基于 Django 的开源电子商务平台。
* alipay：非官方的 Python 支付宝 API。
* merchant：一个可以接收来自多种支付平台支付的 Django 应用。
* money：货币类库with optional CLDR-backed locale-aware formatting and an extensible currency exchange solution.
* python-currencies：显示货币格式以及它的数值。
* django-rest-framework：一个强大灵活的工具，用来构建 web API。
* django-tastypie：为Django 应用开发API。
* django-formapi：为 Django 的表单验证，创建 JSON APIs 。
* flask-api：为 flask 开发的，可浏览 Web APIs 。
* flask-restful：为 flask 快速创建REST APIs 。
* flask-restless：为 SQLAlchemy 定义的数据库模型创建 RESTful APIs 。
* flask-api-utils：为 Flask 处理 API 表示和验证。
* eve：REST API 框架，由 Flask, MongoDB 等驱动。
Pyramid
* cornice：一个Pyramid 的 REST 框架 。
与框架无关的
* falcon：一个用来建立云 API 和 web app 后端的噶性能框架。
* sandman：为现存的数据库驱动系统自动创建 REST APIs 。
* restless：框架无关的 REST 框架 ，基于从 Tastypie 学到的知识。
* ripozo：快速创建 REST/HATEOAS/Hypermedia APIs。
* Authomatic：简单但是强大的框架，身份验证/授权客户端。
* django-allauth：Django 的验证应用。
* django-oauth-toolkit：为 Django 用户准备的 OAuth2。
* django-oauth2-provider：为 Django 应用提供 OAuth2 接入。
* Flask-OAuthlib：OAuth 1.0/a, 2.0 客户端实现，供 Flask 使用。
* OAuthLib：一个 OAuth 请求-签名逻辑通用、 完整的实现。
* python-oauth2：一个完全测试的抽象接口。用来创建 OAuth 客户端和服务端。
* python-social-auth：一个设置简单的社会化验证方式。
* rauth：OAuth 1.0/a, 2.0, 和 Ofly 的 Python 库。
* sanction：一个超级简单的OAuth2 客户端实现。
* jose：JavaScript 对象签名和加密草案的实现。
* PyJWT：JSON Web 令牌草案 01。
* python-jws：JSON Web 签名草案 02 的实现。
* python-jwt：一个用来生成和验证 JSON Web 令牌的模块。
* Jinja2：一个现代的，对设计师友好的模板引擎。
* Chameleon：一个 HTML/XML 模板引擎。 模仿了 ZPT（Zope Page * Templates）, 进行了速度上的优化。
* Genshi：Python 模板工具，用以生成 web 感知的结果。
* Mako：Python 平台的超高速轻量级模板。
* celery：一个异步任务队列/作业队列，基于分布式消息传递。
* huey：小型多线程任务队列。
* mrq：Mr. Queue -一个 Python 的分布式 worker 任务队列， 使用 Redis 和 gevent。
* rq：简单的 Python 作业队列。
* simpleq：一个简单的，可无限扩张的，基于亚马逊 SQS 的队列。
* django-haystack：Django 模块化搜索。
* elasticsearch-py：Elasticsearch 的官方底层 Python 客户端。
* elasticsearch-dsl-py -Elasticsearch 的官方高级 Python 客户端。
* solrpy：solr的 Python 客户端。
* Whoosh：一个快速的纯 Python 搜索引擎库。
* django-activity-stream：从你的站点行为中生成通用活动信息流。
* Stream-Framework：使用 Cassandra 和 Redis 创建动态消息和通知系统。
* django-compressor：将链接和内联的 JavaScript 或 CSS 压缩到一个单独的缓存文件中。
* django-storages：一个针对 Django 的自定义存储后端的工具集合。
* fanstatic：打包、优化，并且把静态文件依赖作为 Python 的包来提供。
* File Conveyor：一个后台驻留的程序，用来发现和同步文件到 CDNs, S3 和 FTP。
* Flask-Assets：帮你将 web 资源整合到你的 Flask app 中。
* jinja-assets-compressor：一个 Jinja 扩展，用来编译和压缩你的资源。
* webassets：为你的静态资源打包、优化和管理生成独一无二的缓存 URL。
Beaker：一个缓存和会话库，可以用在 web 应用和独立 Python脚本和应用上。
* django-cache-machine：Django 模型的自动缓存和失效。
* django-cacheops- 具有自动颗粒化事件驱动失效功能的 ORM。
* django-viewlet：渲染模板，同时具有额外的缓存控制功能。
* dogpile.cache：dogpile.cache 是 Beaker 的下一代替代品，由同一作者开发。
* HermesCache：Python 缓存库，具有基于标签的失效和 dogpile effect 保护功能。
* johnny-cache：django应用缓存框架。
* pylibmc：libmemcached 接口的 Python 封装。
* django-celery-ses：带有 AWS SES 和 Celery 的 Django email 后端。
* envelopes：供人类使用的电子邮件库。
* flanker：一个 email 地址和 Mime 解析库。
* imbox：Python IMAP 库
* inbox.py：Python SMTP 服务器。
* inbox：一个开源电子邮件工具箱。
* lamson：Python 风格的 SMTP 应用服务器。
* mailjet：Mailjet API 实现，用来提供批量发送邮件，统计等功能。
* marrow.mailer：高性能可扩展邮件分发框架。
* modoboa：一个邮件托管和管理平台，具有现代的、简约的 Web UI。
* pyzmail：创建，发送和解析电子邮件。
* Talon：Mailgun 库，用来抽取信息和签名。
* Babel：一个Python 的国际化库。
* Korean：一个韩语词态库。
* furl：一个让处理 URL 更简单小型 Python 库。
* purl：一个简单的，不可变的URL类，具有简洁的 API 来进行询问和处理。
* pyshorteners：一个纯 Python URL 缩短库。
* shorturl- 生成短小 URL 和类似短链的Python 实现。
* webargs：一个解析 HTTP 请求参数的库，内置对流行 web 框架的支持，包括 Flask, Django, Bottle, Tornado和 Pyramid。
* BeautifulSoup：以 Python 风格的方式来对 HTML 或 XML 进行迭代，搜索和修改。
* bleach：一个基于白名单的 HTML 清理和文本链接库。
* cssutils：一个 Python 的 CSS 库。
* html5lib：一个兼容标准的 HTML 文档和片段解析及序列化库。
* lxml：一个非常快速，简单易用，功能齐全的库，用来处理 HTML 和 XML。
* MarkupSafe：为Python 实现 XML/HTML/XHTML 标记安全字符串。
* pyquery：一个解析 HTML 的库，类似 jQuery。
* untangle：将XML文档转换为Python对象，使其可以方便的访问。
* xhtml2pdf：HTML/CSS 转 PDF 工具。
* xmltodict：像处理 JSON 一样处理 XML。
* Scrapy：一个快速高级的屏幕爬取及网页采集框架。
* cola：一个分布式爬虫框架。
* Demiurge：基于PyQuery 的爬虫微型框架。
* feedparser：通用 feed 解析器。
* Grab：站点爬取框架。
* MechanicalSoup：用于自动和网络站点交互的 Python 库。
* portia：Scrapy 可视化爬取。
* pyspider：一个强大的爬虫系统。
* RoboBrowser：一个简单的，Python 风格的库，用来浏览网站，而不需要一个独立安装的浏览器。
* Haul：一个可以扩展的图像爬取工具。
* html2text：将 HTML 转换为 Markdown 格式文本
* lassie：人性化的网页内容检索库。
* micawber -一个小型网页内容提取库，用来从 URLs 提取富内容。
* newspaper：使用 Python 进行新闻提取，文章提取以及内容策展。
* opengraph：一个用来解析开放内容协议(Open Graph Protocol)的 Python模块。
* python-goose：HTML内容/文章提取器。
* python-readability- arc90 公司 readability 工具的 Python 高速端口
* sanitize：为杂乱的数据世界带来调理性。
* sumy：一个为文本文件和 HTML 页面进行自动摘要的模块。
* textract：从任何格式的文档中提取文本，Word，PowerPoint，PDFs 等等。
* Deform：Python HTML 表单生成库，受到了 formish 表单生成库的启发。
* django-bootstrap3- 集成了 Bootstrap 3 的 Django。
* django-crispy-forms：一个 Django 应用，他可以让你以一种非常优雅且 DRY（Don’t repeat yourself） 的方式来创建美观的表单。
* django-remote-forms- 一个平台独立的 Django 表单序列化工具。
* WTForms：一个灵活的表单验证和呈现库。
* WTForms-JSON- 一个 WTForms 扩展，用来处理 JSON 数据。
* Cerberus：A mappings-validator with a variety of rules, normalization-features and simple customization that uses a pythonic schema-definition.
* colander：一个用于对从 XML, JSON，HTML 表单获取的数据或其他同样简单的序列化数据进行验证和反序列化的系统。
* kmatch：一种用于匹配/验证/筛选 Python 字典的语言。
* schema -一个用于对 Python 数据结构进行验证的库。
* Schematics：数据结构验证。
* valideer：轻量级可扩展的数据验证和适配库。
* voluptuous：一个 Python 数据验证库。主要是为了验证传入 Python的 JSON，YAML 等数据。
* django-simple-captcha：一个简单、高度可定制的Django 应用，可以为任何Django表单添加验证码。
* django-simple-spam-blocker- 一个用于Django的简单的电子垃圾屏蔽工具。
* django-taggit：简单的 Django 标记工具。
* Ajenti：一个你的服务器值得拥有的管理面板。
* django-suit：Django 管理界面的一个替代品 (仅对于非商业用途是免费的)。
* django-xadmin：Django admin 的一个替代品，具有很多不错的功能。
* flask-admin：一个用于 Flask 的简单可扩展的管理界面框架。
* flower：一个对 Celery 集群进行实时监控和提供 web 管理界面的工具。
* Grappelli：Django 管理界面的一个漂亮的皮肤。
* Wooey：一个 Django 应用，可以为 Python 脚本创建 web 用户界面。
* Pelican：使用 Markdown 或 ReST 来处理内容， Jinja 2 来制作主题。支持 DVCS, Disqus.。AGPL 许可。
* Cactus：为设计师设计的静态站点生成器。
* Hyde：基于 Jinja2 的静态站点生成器。
* Nikola：一个静态网站和博客生成器。
* Tinkerer：Tinkerer 是一个博客引擎/静态站点生成器，由Sphinx驱动。
* Lektor：一个简单易用的静态 CMS 和博客引擎。
* envoy：比 Python subprocess 模块更人性化。
* sarge：另一 种 subprocess 模块的封装。
* sh：一个完备的 subprocess 替代库。
* multiprocessing：(Python 标准库) 基于进程的“线程”接口。
* threading：(Python 标准库)更高层的线程接口。
* eventlet：支持 WSGI 的异步框架。
* gevent：一个基于协程的 Python 网络库，使用greenlet。
* Tomorrow：用于产生异步代码的神奇的装饰器语法实现。
* asyncio：(Python 标准库) 异步 I/O, 事件循环, 协程以及任务。
* Twisted：一个事件驱动的网络引擎。
* pulsar：事件驱动的并发框架。
* diesel：基于Greenlet 的事件 I/O 框架。
* pyzmq：一个 ZeroMQ 消息库的 Python 封装。
* txZMQ：基于 Twisted 的 ZeroMQ 消息库的 Python 封装。
* AutobahnPython：给 Python 、使用的 WebSocket & WAMP 基于 Twisted 和 asyncio。
* Crossbar：开源统一应用路由(Websocket & WAMP for Python on Autobahn).
* django-socketio：给 Django 用的 WebSockets。
* WebSocket-for-Python：为Python2/3 以及 PyPy 编写的 WebSocket 客户端和服务器库。
* gunicorn：Pre-forked, 部分是由 C 语言编写的。
* uwsgi：uwsgi 项目的目的是开发一组全栈工具，用来建立托管服务， 由 C 语言编写。
* bjoern：异步，非常快速，由 C 语言编写。
* fapws3：异步 (仅对于网络端)，由 C 语言编写。
* meinheld：异步，部分是由 C 语言编写的。
* netius：异步，非常快速。
* paste：多线程，稳定，久经考验。
* rocket：多线程。
* waitress：多线程, 是它驱动着 Pyramid 框架。
* Werkzeug：一个 WSGI 工具库，驱动着 Flask ，而且可以很方便大嵌入到你的项目中去。
* SimpleJSONRPCServer：这个库是 JSON-RPC 规范的一个实现。
* SimpleXMLRPCServer：(Python 标准库) 简单的 XML-RPC 服务器实现，单线程。
* zeroRPC：zerorpc 是一个灵活的 RPC 实现，基于 ZeroMQ 和 MessagePack。
* cryptography：这个软件包意在提供密码学基本内容和方法提供给 Python 开发者。
* hashids：在 Python 中实现 hashids 。
* Paramiko：SSHv2 协议的 Python (2.6+, 3.3+) ，提供客户端和服务端的功能。
* Passlib：安全密码存储／哈希库，
* PyCrypto：Python 密码学工具箱。
* PyNacl：网络和密码学(NaCl) 库的 Python 绑定。
* curses：内建的 ncurses 封装，用来创建终端图形用户界面。
* enaml：使用类似 QML 的Declaratic语法来创建美观的用户界面。
* kivy：一个用来创建自然用户交互（NUI）应用程序的库，可以运行在 Windows, Linux, Mac OS X, Android 以及 iOS平台上。
* pyglet：一个Python 的跨平台窗口及多媒体库。
* PyQt：跨平台用户界面框架 Qt 的 Python 绑定 ，支持Qt v4 和 Qt v5。
* PySide：P跨平台用户界面框架 Qt 的 Python 绑定 ，支持Qt v4。
* Tkinter：Tkinter 是 Python GUI 的一个事实标准库。
* Toga：一个 Python 原生的, 操作系统原生的 GUI 工具包。
* urwid：一个用来创建终端 GUI 应用的库，支持组件，事件和丰富的色彩等。
* wxPython：wxPython 是 wxWidgets C++ 类库和 Python 语言混合的产物。
* PyGObject：GLib/GObject/GIO/GTK+ (GTK+3) 的 Python 绑定
* Flexx：Flexx 是一个纯 Python 语言编写的用来创建 GUI 程序的工具集，它使用 web 技术进行界面的展示。
* Cocos2d：cocos2d 是一个用来开发 2D 游戏， 示例和其他图形/交互应用的框架。基于 pyglet。
* Panda3D：由迪士尼开发的 3D 游戏引擎，并由卡内基梅陇娱乐技术中心负责维护。使用C++编写, 针对 Python 进行了完全的封装。
* Pygame：Pygame 是一组 Python 模块，用来编写游戏。
* PyOgre：Ogre 3D 渲染引擎的 Python 绑定，可以用来开发游戏和仿真程序等任何 3D 应用。
* PyOpenGL：OpenGL 的 Python 绑定及其相关 APIs。
* PySDL2：SDL2 库的封装，基于 ctypes。
* RenPy：一个视觉小说（visual novel）引擎。
* logging：(Python 标准库) 为 Python 提供日志功能。
* logbook：Logging 库的替代品。
* Eliot：为复杂的和分布式系统创建日志。
* Raven：Sentry的 Python 客户端。
* Sentry：实时记录和收集日志的服务器。
* unittest：(Python 标准库) 单元测试框架。
* nose：nose 扩展了 unittest 的功能。
* contexts：一个 Python 3.3+ 的 BDD 框架。受到C#：Machine.Specifications的启发。
* hypothesis：Hypothesis 是一个基于先进的 Quickcheck 风格特性的测试库。
* mamba：Python 的终极测试工具， 拥护BDD。
* PyAutoGUI：PyAutoGUI 是一个人性化的跨平台 GUI 自动测试模块。
* pyshould- Should 风格的断言，基于 PyHamcrest。
* pytest- 一个成熟的全功能 Python 测试工具。
* green- 干净，多彩的测试工具。
* pyvows- BDD 风格的测试工具，受Vows.js的启发。
* Robot Framework：一个通用的自动化测试框架。
* Selenium：Selenium WebDriver 的 Python 绑定。
* locust：使用 Python 编写的，可扩展的用户加载测试工具。
* sixpack：一个和语言无关的 A/B 测试框架。
* splinter：开源的 web 应用测试工具。
* mock：(Python 标准库) 一个用于伪造测试的库。
* doublex：Python 的一个功能强大的 doubles 测试框架。
* freezegun：通过伪造日期模块来生成不同的时间。
* httmock：针对 Python 2.6+ 和 3.2+ 生成 伪造请求的库。
* httpretty：Python 的 HTTP 请求 mock 工具。
* responses：伪造 Python 中的 requests 库的一个通用库。
* VCR.py：在你的测试中记录和重放 HTTP 交互。
* factoryboy：一个 Python 用的测试固件 (test fixtures) 替代库。
* mixer：另外一个测试固件 (test fixtures) 替代库，支持 Django, Flask, SQLAlchemy, Peewee 等。
* modelmommy：为 Django 测试创建随机固件
* coverage：代码覆盖率测量。
* faker：一个 Python 库，用来生成伪数据。
* fake2db：伪数据库生成器。
* radar：生成随机的日期/时间。
* FuckIt.py：FuckIt.py 使用最先进的技术来保证你的 Python 代码无论对错都能继续运行。
* code2flow：把你的 Python 和 JavaScript 代码转换为流程图。
* pycallgraph -这个库可以把你的Python 应用的流程(调用图)进行可视化。
* pysonar2：Python 类型推断和检索工具。
* Flake8：模块化源码检查工具: pep8, pyflakes 以及 co。
* Pylint：一个完全可定制的源码分析器。
* pylama：Python 和 JavaScript 的代码审查工具。
* ipdb：IPython 启用的 pdb。
* pudb：全屏，基于控制台的 Python 调试器。
* pyringe：可以在 Python 进程中附加和注入代码的调试器。
* wdb：一个奇异的 web 调试器，通过 WebSockets 工作。
* winpdb：一个具有图形用户界面的 Python 调试器，可以进行远程调试，基于 rpdb2。
* django-debug-toolbar：为 Django 显示各种调试信息。
* django-devserver：一个 Django 运行服务器的替代品。
* flask-debugtoolbar：django-debug-toolbar 的 flask 版。
* lineprofiler：逐行性能分析。
* memoryprofiler：监控 Python 代码的内存使用。
* profiling：一个交互式 Python 性能分析工具。
* pyelftools：解析和分析 ELF 文件以及 DWARF 调试信息。
* python-statsd：statsd 服务器的 Python 客户端。
* astropy：一个天文学 Python 库。
* bcbio-nextgen：这个工具箱为全自动高通量测序分析提供符合最佳实践的处理流程。
* bccb：生物分析相关代码集合
* Biopython：Biopython 是一组可以免费使用的用来进行生物计算的工具。
* blaze：NumPy 和 Pandas 的大数据接口。
* cclib：一个用来解析和解释计算化学软件包输出结果的库。
* NetworkX：一个为复杂网络设计的高性能软件。
* Neupy：执行和测试各种不同的人工神经网络算法。
* Numba：Python JIT (just in time) 编译器，针对科学用的 Python ，由Cython 和 NumPy 的开发者开发。
* NumPy：使用 Python 进行科学计算的基础包。
* Open Babel：一个化学工具箱，用来描述多种化学数据。
* Open Mining：使用 Python 挖掘商业情报 (BI) (Pandas web 接口)。
* orange：通过可视化编程或 Python 脚本进行数据挖掘，数据可视化，分析和机器学习。
* Pandas：提供高性能，易用的数据结构和数据分析工具。
* PyDy：PyDy 是 Python Dynamics 的缩写，用来为动力学运动建模工作流程提供帮助， 基于 NumPy, SciPy, IPython 和 matplotlib。
* PyMC：马尔科夫链蒙特卡洛采样工具。
* RDKit：化学信息学和机器学习软件。
* SciPy：由一些基于 Python ，用于数学，科学和工程的开源软件构成的生态系统。
* statsmodels：统计建模和计量经济学。
* SymPy：一个用于符号数学的 Python 库。
* zipline：一个 Python 算法交易库。
* matplotlib：一个 Python 2D 绘图库。
* bokeh：用 Python 进行交互式 web 绘图。
* ggplot：ggplot2 给 R 提供的 API 的 Python 版本。
* plotly：协同 Python 和 matplotlib 工作的 web 绘图库。
* pygal：一个 Python SVG 图表创建工具。
* pygraphviz：Graphviz 的 Python 接口。
* PyQtGraph：交互式实时2D/3D/图像绘制及科学/工程学组件。
* SnakeViz：一个基于浏览器的 Python’s cProfile 模块输出结果查看工具。
* vincent：把 Python 转换为 Vega 语法的转换工具。
* VisPy：基于 OpenGL 的高性能科学可视化工具。
* OpenCV：开源计算机视觉库。
* SimpleCV：一个用来创建计算机视觉应用的开源框架。
* Crab：灵活、快速的推荐引擎。
* gensim：人性化的话题建模库。
* hebel：GPU 加速的深度学习库。
* NuPIC：智能计算 Numenta 平台。
* pattern：Python 网络挖掘模块。
* PyBrain：另一个 Python 机器学习库。
* Pylearn2：一个基于 Theano 的机器学习库。
* python-recsys：一个用来实现推荐系统的 Python 库。
* scikit-learn：基于 SciPy 构建的机器学习 Python 模块。
* pydeep：Python 深度学习库。
* vowpalporpoise：轻量级 Vowpal Wabbit 的 Python 封装。
* skflow：一个 TensorFlow 的简化接口(模仿 scikit-learn)。
* dpark：Spark 的 Python 克隆版，一个类似 MapReduce 的框架。
* dumbo：这个 Python 模块可以让人轻松的编写和运行 Hadoop 程序。
* luigi：这个模块帮你构建批处理作业的复杂流水线。
* mrjob：在 Hadoop 或 Amazon Web Services 上运行 MapReduce 任务。
* PySpark：Spark 的 Python API 。
* streamparse：运行针对事实数据流的 Python 代码。集成了Apache Storm。
* CyToolz：Toolz 的 Cython 实现 : 高性能函数式工具。
* fn.py：在 Python 中进行函数式编程 : 实现了一些享受函数式编程缺失的功能。
* funcy：炫酷又实用的函数式工具。
* Toolz：一组用于迭代器，函数和字典的函数式编程工具。
* apache-libcloud：一个为各种云设计的 Python 库。
* boto：Amazon Web Services 的 Python 接口。
* django-wordpress：WordPress models and views for Django.
* facebook-sdk：Facebook 平台的 Python SDK.
* facepy：Facepy 让和 Facebook’s Graph API 的交互变得更容易。
* gmail：Gmail 的 Python 接口。
* google-api-python-client：Python 用的 Google APIs 客户端库。
* gspread：Google 电子表格的 Python API.
* twython：Twitter API 的封装。
* DevOps 工具
* Ansible：一个非常简单的 IT 自动化平台。
* SaltStack：基础设施自动化和管理系统。
* OpenStack：用于构建私有和公有云的开源软件。
* Docker Compose：快速，分离的开发环境，使用 Docker。
* Fabric：一个简单的，Python 风格的工具，用来进行远程执行和部署。
* cuisine：为 Fabric 提供一系列高级函数。
* Fabtools：一个用来编写超赞的 Fabric 文件的工具。
* gitapi：Git 的纯 Python API。
* hgapi：Mercurial 的纯 Python API。
* honcho：Foreman的 Python 克隆版，用来管理基于Procfile的应用。
* pexpect：Controlling interactive programs in a pseudo-terminal like 在一个伪终端中控制交互程序，就像 GNU expect 一样。
* psutil：一个跨平台进程和系统工具模块。
* supervisor：UNIX 的进程控制系统。
* APScheduler：轻巧但强大的进程内任务调度，使你可以调度函数。
* django-schedule：一个 Django 排程应用。
* doit：一个任务执行和构建工具。
* gunnery：分布式系统使用的多用途任务执行工具 ，具有 web 交互界面。
* Joblib：一组为 Python 提供轻量级作业流水线的工具。
* Plan：如有神助地编写 crontab 文件。
* schedule：人性化的 Python 任务调度库。
* Spiff：使用纯 Python 实现的强大的工作流引擎。
* TaskFlow：一个可以让你方便执行任务的 Python 库，一致并且可靠。
* cffi：用来调用 C 代码的外来函数接口。
* ctypes：(Python 标准库) 用来调用 C 代码的外来函数接口。
* PyCUDA：Nvidia CUDA API 的封装。
* SWIG：简化的封装和接口生成器。
* Cython：优化的 Python 静态编译器。使用类型混合使 Python 编译成 C 或 C++ 模块来获得性能的极大提升。
* PeachPy：嵌入 Python 的 x86-64 汇编器。可以被用作 Python 内联的汇编器或者是独立的汇编器，用于 Windows, Linux, OS X, Native Client 或者 Go 。
* PyPy：使用 Python 实现的 Python。解释器使用黑魔法加快 Python 运行速度且不需要加入额外的类型信息。
* Pyston：使用 LLVM 和现代 JIT 技术构建的 Python 实现，目标是为了获得很好的性能。
* Stackless Python：一个强化版的 Python。
* Python(x,y)：面向科学应用的 Python 发行版，基于 Qt 和 Spyder。
* pythonlibs：非官方的 Windows 平台 Python 扩展二进制包。
* PythonNet：Python 与 .NET 公共语言运行库 (CLR)的集成。
* PyWin32：针对 Windows 的Python 扩展。
* WinPython：Windows 7/8 系统下便携式开发环境。
* Mininet：一款流行的网络模拟器以及用 Python 编写的 API。
* POX：一个针对基于 Python 的软件定义网络应用（例如 OpenFlow SDN 控制器）的开源开发平台。
* Pyretic：火热的 SDN 编程语言中的一员，为网络交换机和模拟器提供强大的抽象能力。
* SDX Platform：基于 SDN 的 IXP 实现，影响了 Mininet, POX 和 Pyretic。
* ino -操作Arduino的命令行工具。
* Pyro：Python 机器人编程库。
* PyUserInput：跨平台的，控制鼠标和键盘的模块。
* scapy：一个非常棒的操作数据包的库。
* wifi：一个 Python 库和命令行工具用来在 Linux 平台上操作WiFi。
* Pingo：Pingo 为类似Raspberry Pi，pcDuino， Intel Galileo等设备提供统一的API用以编程。
* Python-Future：这就是 Python 2 和 Python 3 之间丢失的那个兼容性层。
* Python-Modernize：使 Python 代码更加现代化以便最终迁移到 Python 3。
* Six：Python 2 和 3 的兼容性工具。
* blinker：一个快速的 Python 进程内信号/事件分发系统。
* itsdangerous：一系列辅助工具用来将可信的数据传入不可信的环境。
* pluginbase：一个简单但是非常灵活的 Python 插件系统。
* Pychievements：一个用来创建和追踪成就的 Python 框架。
* Tryton：一个通用商务框架。
* algorithms -一个 Python 算法模块
* python-patterns：Python 设计模式的集合。
* sortedcontainers：快速，纯 Python 实现的SortedList，SortedDict 和 SortedSet 类型。
* Elpy：Emacs Python 开发环境。
* Sublime Text
* SublimeJEDI：一个 Sublime Text 插件，用来使用超赞的自动补全库 Jedi。
* Anaconda：Anaconda 把你的 Sublime Text 3 变成一个功能齐全的 Python IDE。
* Vim
* YouCompleteMe：引入基于 Jedi 的 Python 自动补全引擎。
* Jedi-vim：绑定 Vim 和 Jedi 自动补全库对 Python 进行自动补全。
* Python-mode：将 Vim 变成 Python IDE 的一款多合一插件。
* Visual Studio
* PTVS：Visual Studio 的 Python 工具
* PyCharm：商业化的 Python IDE ，由 JetBrains 开发。也有免费的社区版提供。
* LiClipse：基于 Eclipse 的免费多语言 IDE 。使用 PyDev 来支持 Python 。
* Spyder：开源 Python IDE。
* Travis CI：一个流行的工具，为你的开源和私人项目提供持续集成服务。(仅支持 GitHub)
* CircleCI：一个持续集成工具，可以非常快速的进行并行测试。 (仅支持 GitHub)
* Vexor CI：一个为私人 app 提供持续集成的工具，支持按分钟付费。
* Wercker：基于 Docker 平台，用来构建和部署微服务。
* Codacy：自动化代码审查，更加快速的发布高质量代码。对于开源项目是免费的。
* QuantifiedCode：一个数据驱动、自动、持续的代码审查工具。
* Tornado： 和其他Python框架的架构可谓大相径庭，Request的处理方式也很舒服，特别适合REST，谁用谁知道
* Mako： 个人认为是最好的Template，简单 性能好
* SQLAlchemy: 快一统ORM了吧
* Quixote：其实还是蛮好用的
* pyQuery: 用jQuery的语法写爬虫 略爽
```