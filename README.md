# Search-Engine

### 📊 参考目录结构

```text
Search-Engine/
├── bin/
├── build/
├── CMakeLists.txt
├── conf/
│   └── config.conf
├── data/
│   ├── corpus/
│   │   ├── CN/
│   │   ├── EN/  
│   │   └── webpages/
│   ├── dict/
│   ├── index/
│   └── stopwords/
│       ├── cn_stopwords.txt
│       └── en_stopwords.txt
├── docs/
│   ├── 搜索引擎项目.pdf
│   └── 项目第一期开发思路.md
├── include/
│   ├── common/
│   │   ├── DirectoryScanner.h
│   │   └── TextUtils.h
│   ├── offline/
│   │   ├── KeywordProcessor.h
│   │   └── PageProcessor.h
│   └── online/
├── LICENSE
├── README.md
├── src/
│   ├── common/
│   │   ├── DirectoryScanner.cpp
│   │   └── TextUtils.cpp
│   ├── offline/
│   │   ├── KeywordProcessor.cpp
│   │   ├── offline_main.cpp
│   │   └── PageProcessor.cpp
│   └── online/
└── tests/
