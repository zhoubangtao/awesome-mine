# Awesome Mine

A curated list of awesome frameworks, libraries and software usually used by myself. Inspired by [awesome-python](https://github.com/vinta/awesome-python).

- [Awesome Mine](#awesome-mine)
    - [Environment Management](#environment-management)
    - [Package Management](#package-management)
    - [Package Repositories](#package-repositories)
    - [Distribution](#distribution)
    - [Build Tools](#build-tools)
    - [Interactive Interpreter](#interactive-interpreter)
    - [Files](#files)
    - [Date and Time](#date-and-time)
    - [Text Processing](#text-processing)
    - [Specific Formats Processing](#specific-formats-processing)
    - [Natural Language Processing](#natural-language-processing)
    - [Documentation](#documentation)
    - [Configuration](#configuration)
    - [Command-line Tools](#command-line-tools)
    - [Downloader](#downloader)
    - [Imagery](#imagery)
    - [OCR](#ocr)
    - [Audio](#audio)
    - [Video](#video)
    - [Geolocation](#geolocation)
    - [HTTP](#http)
    - [Database](#database)
    - [Database Drivers](#database-drivers)
    - [ORM](#orm)
    - [Web Frameworks](#web-frameworks)
    - [Permissions](#permissions)
    - [CMS](#cms)
    - [E-commerce](#e-commerce)
    - [RESTful API](#restful-api)
    - [Authentication](#authentication)
    - [Template Engine](#template-engine)
    - [Queue](#queue)
    - [Search](#search)
    - [News Feed](#news-feed)
    - [Asset Management](#asset-management)
    - [Caching](#caching)
    - [Email](#email)
    - [Internationalization](#internationalization)
    - [URL Manipulation](#url-manipulation)
    - [HTML Manipulation](#html-manipulation)
    - [Web Crawling](#web-crawling)
    - [Web Content Extracting](#web-content-extracting)
    - [Forms](#forms)
    - [Data Validation](#data-validation)
    - [Anti-spam](#anti-spam)
    - [Tagging](#tagging)
    - [Admin Panels](#admin-panels)
    - [Static Site Generator](#static-site-generator)
    - [Processes and Threads](#processes-and-threads)
    - [Concurrency and Networking](#concurrency-and-networking)
    - [WebSocket](#websocket)
    - [WSGI Servers](#wsgi-servers)
    - [RPC Servers](#rpc-servers)
    - [Cryptography](#cryptography)
    - [GUI](#gui)
    - [Game Development](#game-development)
    - [Logging](#logging)
    - [Testing](#testing)
    - [Code Analysis and Linter](#code-analysis-and-linter)
    - [Debugging Tools](#debugging-tools)
    - [Science and Data Analysis](#science-and-data-analysis)
    - [Data Visualization](#data-visualization)
    - [Computer Vision](#computer-vision)
    - [Machine Learning](#machine-learning)
    - [Functional Programming](#functional-programming)
    - [MapReduce](#mapreduce)
    - [Third-party APIs](#third-party-apis)
    - [DevOps Tools](#devops-tools)
    - [Job Scheduler](#job-scheduler)
    - [Foreign Function Interface](#foreign-function-interface)
    - [High Performance](#high-performance)
    - [Network Virtualization and SDN](#network-virtualization-and-sdn)
    - [Hardware](#hardware)
    - [Compatibility](#compatibility)
    - [Miscellaneous](#miscellaneous)
    - [Algorithms and Design Patterns](#algorithms-and-design-patterns)
    - [Editor Plugins](#editor-plugins)
    - [IDEs](#ides)
- [Resources](#resources)
    - [Websites](#websites)
    - [Weekly](#weekly)
    - [Twitter](#twitter)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing)

- - -

## Environment Management

*Libraries for Python version and environment management.*

* [p](https://github.com/qw3rtman/p) - Dead Simple Interactive Python Version Management.
* [pyenv](https://github.com/yyuu/pyenv) - Simple Python version management.
* [virtualenv](https://pypi.python.org/pypi/virtualenv) - A tool to create isolated Python environments.
* [virtualenvwrapper](https://pypi.python.org/pypi/virtualenvwrapper) - A set of extensions to virtualenv.
* [virtualenv-api](https://github.com/sjkingo/virtualenv-api) - An API for virtualenv and pip.
* [pew](https://pypi.python.org/pypi/pew/) - A set of tools to manage multiple virtual environments.
* [Vex](https://github.com/sashahart/vex) - Run a command in the named virtualenv.
* [PyRun](https://www.egenix.com/products/python/PyRun/) - A one-file, no-installation-needed version of Python.

## Operation System

*Libraries or Tools for Operation System.*

* [Netdata](https://github.com/firehol/netdata) - Real-time performance monitoring, done right! http://netdata.firehol.org

## Mac OSX

*Libraries or Tools for Mac OSX.*

* [amix-vimrc](https://github.com/amix/vimrc) - The ultimate Vim configuration: vimrc 
* [ruchee-vimrc](https://github.com/ruchee/vimrc) - Ruchee's Vim Config Files 
* [vgod-vimrc](https://github.com/vgod/vimrc) - vgod's vimrc 
* [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) - A delightful community-driven framework for managing your zsh configuration.
* [tmux](https://tmux.github.io/) - tmux is a terminal multiplexer: it enables a number of terminals to be created, accessed, and controlled from a single screen. tmux may be detached from a screen and continue running in the background, then later reattached.
* [tmux-powerline](https://github.com/erikw/tmux-powerline) - Statusbar configuration for tmux that looks like vim-powerline and consist of dynamic segments.
* [screen](http://www.gnu.org/software/screen/) - Screen is a full-screen window manager that multiplexes a physical terminal between several processes, typically interactive shells.
* [zsh](http://zsh.sourceforge.net/Guide/zshguide.html) - a zsh guide


## Penetration Testing


* [metasploit-framework](https://github.com/rapid7/metasploit-framework/) - World's most used penetration testing software


## Big Data

*Framework, tools and libraries for Big Data.*

* [Spotify Luigi](https://github.com/spotify/luigi) - a Python package for building complex pipelines of batch jobs. It handles dependency resolution, workflow management, visualization, handling failures, command line integration, and much more.
* [Caravel](https://github.com/airbnb/caravel) - Caravel is a data exploration platform designed to be visual, intuitive, and interactive

## Database Tools

*Database tools, like replication, binlog, CDC and so on.*

* MySQL
    * [mysql-binlog-connector-java](https://github.com/shyiko/mysql-binlog-connector-java) - MySQL Binary Log connector
    * [open-replicator](https://github.com/whitesock/open-replicator) -  Open Replicator is a high performance MySQL binlog parser written in Java
    * [mypipe](https://github.com/mardambey/mypipe) - MySQL binary log consumer with the ability to act on changed rows and publish changes to different systems with emphasis on Apache Kafka. 
    * [mydit](https://github.com/ngocdaothanh/mydit) - MySQL to MongoDB data replicator 
    * [python-mysql-replication](https://github.com/noplay/python-mysql-replication) - Pure Python Implementation of MySQL replication protocol build on top of PyMYSQL

* PostgreSQL
    * [pylogicaldecoding](https://github.com/lisael/pylogicaldecoding) - Python interface to PostgreSQL logical decoding 
    * [bottledwater-pg](https://github.com/confluentinc/bottledwater-pg) - Change data capture from PostgreSQL into Kafka 
    
## Usefull Awesomes

*some usefull awesome list*

* [awesome-bigdata](https://github.com/onurakpolat/awesome-bigdata) - A curated list of awesome big data frameworks, ressources and other awesomeness. 
    
## Something Interesting

*something interesting.*

* [showterm](http://showterm.io/) - Termshows are purely text based. This makes them ideal for demoing instructions (as the user can copy-paste), making fail-safe "live-coding" sessions (plain text is very scalable), and sharing all your l33t terminal hacks.
* [asciinema](https://asciinema.org/) - ascii camera

*Continuous Integration and Automation Test*

* [macaca](https://github.com/macacajs/macaca) - Automation Test with ease
* [reliable](https://github.com/reliablejs/reliable) - Distributed reliable continuous integration service
