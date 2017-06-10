<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="http://github.com/LewisJEllis/awesome-lua">LewisJEllis/awesome-lua</a> with ranks
</p>
---
# Awesome Lua [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](https://github.com/sindresorhus/awesome)

> A curated list of quality Lua [packages](#packages) and [resources](#resources).

Inspired by the lists [awesome](https://github.com/sindresorhus/awesome), [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness), and [awesome-nodejs ★17249](https://github.com/sindresorhus/awesome-nodejs).


## Packages
- [Implementations, Interpreters, and Bindings](#implementations-interpreters-and-bindings)
- [Package Managers](#package-managers)
- [Debugging and Profiling](#debugging-and-profiling)
- [IDEs and Plugins](#ides-and-plugins)
- [Utility Belts](#utility-belts)
- [Game Engines](#game-engines)
- [Game Development](#game-development)
- [Logging](#logging)
- [Web/Networking Platforms](#webnetworking-platforms)
- [OpenResty](#openresty)
- [Command-line Utilities](#command-line-utilities)
- [Concurrency and Multithreading](#concurrency-and-multithreading)
- [Templating](#templating)
- [Documentation](#documentation)
- [Object-oriented Programming](#object-oriented-programming)
- [Filesystem and OS](#filesystem-and-os)
- [Time and Date](#time-and-date)
- [Image Manipulation](#image-manipulation)
- [Digital Signal Processing](#digital-signal-processing)
- [Hardware and Embedded Systems](###hardware-and-embedded-systems)
- [Math and Scientific Computing](#math-and-scientific-computing)
- [Parsing](#parsing)
- [Humanize](#humanize)
- [Compression](#compression)
- [Cryptography](#cryptography)
- [Network](#network)
- [Data Stores](#data-stores)
- [Testing](#testing)
- [Foreign Function Interfaces](#foreign-function-interfaces)
- [Analysis Tools and ASTs](#analysis-tools-and-asts)
- [Experimental, etc](#experimental-etc)
- [Scriptable by Lua](#scriptable-by-lua)
- [Miscellaneous](#miscellaneous)


## Resources
- [References](#references)
- [Style Guides](#style-guides)
- [Tutorials](#tutorials)
- [Articles](#articles)
- [Talks & Slides](#talks--slides)
- [Books](#books)
- [Other Lists](#other-lists)


### Implementations, Interpreters, and Bindings
- [Lua](http://www.lua.org/download.html) - Lua's original ANSI C interpreter.
- [LuaJIT](http://luajit.org/luajit.html) - High-performance Just-In-Time compiler for Lua.
- [LLVM-Lua ★26 ⏳1Y](https://github.com/neopallium/llvm-lua) - Compiles Lua to LLVM.
- [lua.vm.js](https://github.com/kripken/lua.vm.js) - Lua VM on the web; a direct port of the C interpreter via LLVM, emscripten, and asm.js.
- [Moonshine ★381](https://github.com/gamesys/moonshine) - A Lua VM implemented in JavaScript. Slower than lua.vm.js, but with better docs, examples, and JS interfacing.
- [MoonSharp ★406](https://github.com/xanathar/moonsharp) - A Lua interpreter written entirely in C# for the .NET, Mono and Unity platforms.
- [UniLua ★834](https://github.com/xebecnan/UniLua) - A pure C# implementation of Lua 5.2, focused on compatibility with the Unity game engine.
- [lupa ★374](https://github.com/scoder/lupa) - Python bindings to LuaJIT2.
- [golua ★324](https://github.com/aarzilli/golua) - Golang bindings to the Lua C API.
- [GopherLua ★1666](https://github.com/yuin/gopher-lua) - Lua 5.1 VM and compiler implemented in Go with Go APIs.

Note: From LuaJIT to Lua to lua.vm.js to Moonshine, a basic benchmark sees performance drop by roughly a factor of 6 with each hop.


### Package Managers
- [LuaRocks](http://luarocks.org/en) - Allows you to install Lua modules as packages called "rocks", which contain version and dependency information. Much like npm or pip.
- [MoonRocks](https://rocks.moonscript.org/) - Public Lua rock repository, website, and uploading tool. Default server used by LuaRocks.


### Debugging and Profiling
- [ProFi](https://gist.github.com/perky/2838755) - Simple profiler that works with LuaJIT and produces a report file.
- [luatrace ★108 ⏳1Y](https://github.com/geoffleyland/luatrace) - Toolset for tracing/analyzing/profiling script execution and generating detailed reports.
- [StackTracePlus ★122](https://github.com/ignacio/StackTracePlus) - Drop-in upgrade to Lua's stack traces which adds local context and improves readability.
- [MobDebug ★327](https://github.com/pkulchenko/MobDebug) - Powerful remote debugger with breakpoints and stack inspection. Used by ZeroBraneStudio.
- [lovebird ★132](https://github.com/rxi/lovebird) - Browser-based debug console. Originally made for LÖVE, but works in any project with LuaSocket support.


### IDEs and Plugins
- [Lua Development Tools](http://www.eclipse.org/koneki/ldt/) - Eclipse plugin which provides code completion, debugging, and more. Built on Metalua.
- [Lua for IDEA](https://bitbucket.org/sylvanaar2/lua-for-idea/wiki/Home) - IntelliJ IDEA plugin which, among other things, provides code completion, smart highlighting, and experimental debugging.
- [ZeroBraneStudio](http://studio.zerobrane.com/) - Lightweight, customizable, cross-platform Lua-dedicated IDE with code completion and analysis, written in Lua. Has broad debugging support for numerous Lua engines.
- [Babelua](http://babelua.codeplex.com/) - Lua editor/debugger, extension for Visual Studio 2012/2013. Has code highlight, auto-completion, syntax checking and formatting, file previewing, debugging capabilities integrated into Visual Studio.

### Utility Belts
- [Lua Fun](https://github.com/rtsisyk/luafun) - High-performance functional programming library designed for LuaJIT.
- [Moses ★316](https://github.com/Yonaba/Moses) - Functional programming utility belt, inspired by Underscore.js.
- [Penlight ★699](https://github.com/stevedonovan/Penlight) - Broad, heavyweight utility library, inspired by Python's standard libs. Provides the batteries that Lua doesn't.
- [lua-stdlib ★145 ⏳1Y](https://github.com/lua-stdlib/lua-stdlib) - Middle-weight standard library extension; adds some useful data structures, utility functions, and basic functional stuff.
- [Microlight ★91 ⏳1Y](https://github.com/stevedonovan/Microlight) - A little library of useful Lua functions; the 'extra light' version of Penlight.


### Game Engines
- [LÖVE 2D](http://love2d.org/) - Desktop game development platform. Cross-platform, feature-complete, well-adopted.
- [Corona SDK](https://coronalabs.com/products/corona-sdk/) - Development platform for iOS and Android. Proprietary, but used by numerous top games and apps, totaling over 150 million downloads.
- [MOAI](http://getmoai.com/) - Open source, cross-platform, mobile game development framework. Minimalist C++ engine powered by Lua scripting.
- [Drystal](https://drystal.github.io/) - Open source, games can run on Linux or on any platform with a recent web browser.
- [Amulet](http://www.amulet.xyz/) - Open source, audio/visual toolkit suitable for small games and experimentation. It runs on Windows, Mac, Linux, HTML5 and iOS.
- [gengine](https://gengine.bitballoon.com/) - A 2d game engine for fast development, using entities and components system, for Linux, Windows and HTML5.


### Game Development
- Corona
  - [Coronium.io](http://coronium.io/) - Simple cloud platform supporting analytics, data objects, user management, and more.
- LÖVE
  - [awesome-love2d](https://github.com/JanWerder/awesome-love2d) - A list like this one, but focused on game dev and the LÖVE platform.
  - [lurker ★89 ⏳2Y](https://github.com/rxi/lurker) - Shortens the iteration cycle by auto-swapping changed Lua files in a running LÖVE project.
  - [HUMP](http://vrld.github.io/hump) - A set of lightweight helpers for LÖVE; a game-oriented utility belt.
- MOAI
  - [moaifiddle](http://moaifiddle.com) - Edit and share short scripts for the MOAI game engine and run them in the browser using WebGL.
- [Jumper ★384](https://github.com/Yonaba/Jumper) - Fast, lightweight, and easy-to-use pathfinding library for grid-based games.
- [lume ★192](https://github.com/rxi/lume) - Utility belt library geared toward game development.
- [NoobHub ★159](https://github.com/Overtorment/NoobHub) - Network multiplayer for Corona, LÖVE, and more, following a simple pub-sub model.
- Collision detection
  - [bump.lua ★317](https://github.com/kikito/bump.lua) - Minimal rectangle-based collision detection which handles tunnelling and basic collision resolution.
  - [HardonCollider](http://vrld.github.io/HardonCollider/) - Detect collisions between arbitrarily positioned and rotated shapes of any type.
- Tweening
  - [flux ★112](https://github.com/rxi/flux) - A fast, lightweight tweening library for Lua with easing functions and the ability to group tweens together.
  - [tween.lua ★246 ⏳1Y](https://github.com/kikito/tween.lua) - Small library for tweening, with several easing functions.
- Examples
  - [termtris ★391 ⏳2Y](https://github.com/tylerneylon/termtris) - A tetris clone, written in literate style with "an emphasis on learn-from-ability".
  - [PacPac ★314 ⏳2Y](https://github.com/tylerneylon/pacpac) - A Pac-man clone, made with LÖVE.
  - [Mari0 ★163](https://github.com/Stabyourself/mari0) - Fusion of Mario and Portal, made with LÖVE. See also its [wikipedia entry](https://en.wikipedia.org/wiki/Mari0).
  - [Journey to the Center of Hawkthorne ★765](https://github.com/hawkthorne/hawkthorne-journey) - 2D platformer based on Community's [Digital Estate Planning](https://en.wikipedia.org/wiki/Digital_Estate_Planning) episode, made with LÖVE.


### Logging
- [log-lua ★57](https://github.com/moteus/lua-log) - Asynchronous logging library with pluggable writers for filesystem, network, ZeroMQ, and more.


### Web/Networking Platforms
- [OpenResty](http://openresty.org/) - A fast and scalable web application platform created by extending Nginx with Lua. Today's de-facto Lua web platform, used heavily by Cloudflare, Taobao, Tencent, and others.
- [turbo](http://www.turbolua.org/) - Event-driven, non-blocking, LuaJIT-based networking suite and framework, inspired by Tornado.
- [Kepler Project](http://www.keplerproject.org/) - A collection of web-oriented projects using a common set of standards and components.
- [Pegasus.lua](http://github.com/EvandroLG/pegasus.lua) - Pegasus.lua is a http server to work with web applications written in Lua language.

### OpenResty
- [awesome-resty ★740](https://github.com/bungle/awesome-resty) - A list like this one, but focused on OpenResty.
- Core platform
  - [ngx_lua](https://www.nginx.com/resources/wiki/modules/lua/) - The core piece of OpenResty. Embeds Lua in Nginx and exposes, among other things, the cosocket API for non-blocking sockets (compatible with LuaSocket's API).
  - [OpenResty GitHub Organization](https://github.com/openresty) - Home of the repositories for ngx_lua, ngx_openresty, and many related modules.
- Third-party modules
  - [lua-resty-http ★538](https://github.com/pintsized/lua-resty-http) - Lua HTTP client driver, built on the cosocket API.
- Frameworks & tools
  - [Lapis](http://leafo.net/lapis/) - Full-stack framework for Lua and OpenResty. Like the Django or Rails of Lua. Supports Moonscript.
  - [ledge ★258](https://github.com/pintsized/ledge) - Lua module providing scriptable, RFC-compliant HTTP cache functionality.
  - [Sailor ★718](https://github.com/sailorproject/sailor) — An MVC web framework compatible with OpenResty, Apache and other webservers.
  - [Kong ★10209](https://github.com/mashape/kong) - Microservice & API Management Layer 

Search this page for 'OpenResty' to find related packages under other categories (data stores in particular).


### Command-line Utilities
- [ansicolors ★44 ⏳2Y](https://github.com/kikito/ansicolors.lua) - Simple function for printing to the console in color.
- [cliargs ★46](https://github.com/amireh/lua_cliargs) - A simple command-line argument parsing module.
- [lua-term ★55](https://github.com/hoelzro/lua-term) - Terminal operations and manipulations.
- [argparse ★86 ⏳1Y](https://github.com/mpeterv/argparse) - A feature-rich command line parser inspired by argparse for Python.

### Concurrency and Multithreading
- Coroutine-based multitasking:
  - [Lumen ★96](https://github.com/xopxe/Lumen) - Simple concurrent task scheduling.
  - [ConcurrentLua ★144 ⏳2Y](https://github.com/lefcha/concurrentlua) - Implements an Erlang-style message-passing concurrency model.
- Multithreading:
  - [llthreads ★112 ⏳1Y](https://github.com/Neopallium/lua-llthreads) - A simple wrapper for low-level pthreads & WIN32 threads.
  - [lanes ★195](https://github.com/LuaLanes/lanes) - Library implementing a message passing model with one OS thread per Lua thread.
  - [luaproc ★73](https://github.com/askyrme/luaproc) - Message-passing model which allows multiple threads per OS thread and easily generalizes across a network. See also [the paper](http://www.inf.puc-rio.br/~roberto/docs/ry08-05.pdf) where it originated.

For more on the differences (particularly between `lanes` and `luaproc`), see this [comparison](http://cmr.github.io/lanes/comparison.html) of options; somewhat dated, but covers how each one works and the significant differences.


### Templating
- [lustache](http://olivinelabs.com/lustache/) - Mustache template implementation.
- [etlua ★83 ⏳1Y](https://github.com/leafo/etlua) - Embedded Lua templates, ERB-style.
- [lua-resty-template ★432](https://github.com/bungle/lua-resty-template) - Lua-oriented template engine for OpenResty, somewhat Jinja-like.


### Documentation
- [LDoc](http://stevedonovan.github.io/ldoc/) - Documentation generator which modernizes and extends [LuaDoc](http://keplerproject.github.io/luadoc/).
- [Locco](http://rgieseke.github.io/locco/) - Lua port of [Docco](http://jashkenas.github.io/docco/), the "quick-and-dirty, hundred-line-long, literate-programming-style documentation generator".
- [docroc ★6 ⏳1Y](https://github.com/bjornbytes/docroc) - Parse comments into a Lua table to generate documentation.


### Object-oriented Programming
- [30log ★218](https://github.com/Yonaba/30log) - Minimalist OOP library with basic classes, inheritance, and mixins in 30 lines.
- [middleclass ★805](https://github.com/kikito/middleclass) - Simple but robust OOP library with inheritance, methods, metamethods, class variables and mixins.


### Filesystem and OS
- [LuaFileSystem](http://keplerproject.github.io/luafilesystem/) - Extends and complements Lua's built-in set of filesystem functions.
- [luaposix ★228](https://github.com/luaposix/luaposix) - Bindings for POSIX APIs, including curses.


### Time and Date
- [LuaDate ★92](https://github.com/Tieske/date) - Date and time module with parsing, formatting, addition/subtraction, localization, and ISO 8601 support.
- [cron.lua ★83 ⏳3Y](https://github.com/kikito/cron.lua) - Time-related functions for Lua, inspired by JavaScript's setTimeout and setInterval.


### Image Manipulation
- [magick ★232](https://github.com/leafo/magick) - Lua bindings to ImageMagick for LuaJIT using FFI.


### Digital Signal Processing
- [LuaFFT](https://github.com/vection/luafft) - An easy to use Fast Fourier Transformation package in pure Lua.
- [Worp](http://worp.zevv.nl/about.html) - Sound/music/DSP engine written for LuaJIT.


### Hardware and Embedded Systems
- [eLua](http://www.eluaproject.net/) - Lua, extended with optimizations and specific features for efficient and portable embedded software development.


### Math and Scientific Computing
- [SciLua](http://scilua.org/) - Numerical/scientific computing framework built on LuaJIT, with an interface to R.
- [Torch7](http://torch.ch/) - Scientific computing framework with wide support for machine learning algorithms, used by Facebook, Google, and more.
- [lhf's Lua Tools](http://www.tecgraf.puc-rio.br/~lhf/ftp/lua/) - Assorted libraries and tools, many math-related.


### Parsing
- JSON
  - [lua-cjson ★387](https://github.com/mpx/lua-cjson) - Blazing fast JSON encoding/decoding implemented in C and exposed to Lua.
  - [luajson ★188](https://github.com/harningt/luajson) - JSON encoder/decoder implemented in Lua on top of LPeg.
  - [dkjson](http://dkolf.de/src/dkjson-lua.fsl/home) - JSON encoder/decoder implemented in pure Lua.
- XML
  - [LuaExpat](https://matthewwild.co.uk/projects/luaexpat/) - SAX XML parser via binding to the Expat library.
  - [SLAXML ★89 ⏳1Y](https://github.com/Phrogz/SLAXML) - Pure Lua SAX-like streaming XML parser.
- [lyaml ★59](https://github.com/gvvaughan/lyaml) - YAML encoding/decoding via binding to LibYAML.
- [LPeg](http://www.inf.puc-rio.br/~roberto/lpeg/) - A pattern-matching library for Lua, based on Parsing Expression Grammars.
- [lunamark ★111](https://github.com/jgm/lunamark) - Converts Markdown to other textual formats including HTML and LaTeX. Uses LPeg for fast parsing.


### Humanize
- [i18n.lua ★73](https://github.com/kikito/i18n.lua) - Internationalization library with locales, formatting, and pluralization.
- [inspect.lua ★394](https://github.com/kikito/inspect.lua) - Human-readable representation of Lua tables.
- [serpent ★158](https://github.com/pkulchenko/serpent) - Serializer and pretty printer.
- [Ser ★51 ⏳1Y](https://github.com/gvx/Ser) - Dead simple serializer with good performance.


### Compression
- [lua-zlib ★116](https://github.com/brimworks/lua-zlib) - Simple streaming interface to zlib for gzip/gunzip.
- [lua-zip ★31 ⏳1Y](https://github.com/brimworks/lua-zip) - Lua binding to libzip. Reads and writes zip files.


### Cryptography
- [LuaCrypto ★63 ⏳1Y](https://github.com/mkottman/luacrypto) - Lua bindings to OpenSSL.
- [lua-lockbox ★203](https://github.com/somesocks/lua-lockbox) - A collection of cryptographic primitives written in pure Lua.
- [luatweetnacl ★7](https://github.com/philanc/luatweetnacl) - Bindings to tweetnacl, modern high-security cryptographic library.

### Network
- [LuaSocket ★632](https://github.com/diegonehab/luasocket) - Networking extension which provides a socket API for TCP and UDP, and implements HTTP, FTP, and SMTP.
- [lua-websockets ★218](https://github.com/lipp/lua-websockets) - WebSocket client and server modules. Webserver-agnostic, implemented in Lua on top of LuaSocket.


### Data Stores
- [LuaSQL](http://www.keplerproject.org/luasql/) - Simple interface for connecting to ODBC, ADO, Oracle, MySQL, SQLite and PostgreSQL.
- [redis-lua ★432 ⏳1Y](https://github.com/nrk/redis-lua) - Pure Lua client library for Redis.
- [pgmoon ★129](https://github.com/leafo/pgmoon) - Lua PostgreSQL driver for OpenResty and others.
- [lua-resty-mysql ★322](https://github.com/openresty/lua-resty-mysql) - Lua MySQL driver for OpenResty.
- [lua-resty-redis ★796](https://github.com/openresty/lua-resty-redis) - Lua Redis client driver for OpenResty.
- [lua-resty-cassandra ★60 ⏳2Y](https://github.com/jbochi/lua-resty-cassandra) - Lua Cassandra client driver for OpenResty and others.


### Testing
- [busted](http://olivinelabs.com/busted/) - BDD-style unit testing framework with great docs and Moonscript support.
- [telescope ★122](https://github.com/norman/telescope) - Flexible and highly customizable testing library.
- [luassert ★47](https://github.com/Olivine-Labs/luassert) - Assertion library extending Lua's built-in assertions.
- [lust ★20](https://github.com/bjornbytes/lust) - Minimal test framework.


### Foreign Function Interfaces
- [LuaJIT FFI](http://luajit.org/ext_ffi.html) - LuaJIT's mechanism for calling external C functions and using C data structures from pure Lua code.
- [luaffi ★282](https://github.com/jmckaskill/luaffi) - Standalone FFI library, compatible with the LuaJIT FFI interface.


### Analysis Tools and ASTs
- [luadec51 ★166 ⏳1Y](https://github.com/sztupy/luadec51) - Lua Decompiler for Lua version 5.1.
- [luacov](http://keplerproject.github.io/luacov/) - Simple coverage analyzer, used by busted and telescope for checking test coverage.
- [luacheck ★473](https://github.com/mpeterv/luacheck) - Simple static analyzer which detects accidental globals and undefined or shadowed locals.
- [Metalua ★246 ⏳3Y](https://github.com/fab13n/metalua) - Pure Lua parser and compiler, used for generating ASTs. A number of other tools make use of the Metalua parser in this way.
- [LuaInspect ★136 ⏳1Y](https://github.com/davidm/lua-inspect) - Lua's most powerful code analysis and linting tool, built on Metalua. Used by ZeroBraneStudio, among others.
- [LuaMinify ★117](https://github.com/stravant/LuaMinify) - Minifier which also brings its own static analysis tools, lexer, and parser.
- [Typed Lua ★307](https://github.com/andremm/typedlua) - A typed superset of Lua that compiles to plain Lua.


### Experimental, etc
- [punchdrunk.js ★72 ⏳1Y](https://github.com/TannerRogalsky/punchdrunk) - Moonshine + LÖVE API reimplementation = run LÖVE games in the browser.
- [luvit ★2577](https://github.com/luvit/luvit) - Node.js's underlying architecture (libUV) with Lua on top instead of JavaScript.
- [graphql-lua ★55](https://github.com/bjornbytes/graphql-lua) - Lua implementation of [GraphQL](http://graphql.org/).


### Scriptable by Lua
- [luakit](https://luakit.github.io/luakit/) - Fast, small, webkit based browser framework extensible by Lua.
- [Hammerspoon](http://www.hammerspoon.org) - A powerful, extensible OS X automation tool. A community-maintained fork of [Mjolnir](http://www.mjolnir.io/).
- [kpie ★21 ⏳1Y](https://github.com/skx/kpie) - A scripting utility to juggle windows.
- [lumail](https://lumail.org/) - A console-based mail client, with extensive scripting capabilities.
- [AwesomeWM](http://awesome.naquadah.org) - A highly configurable and extensible window manager for X, scripted and configured by Lua.
- [Textadept](http://foicica.com/textadept/) - Extremely lightweight, customizable, cross-platform editor, written (mostly) in (and scripted by) Lua.
- [KoReader ★2991](https://github.com/koreader/koreader) - An ebook reader application supports PDF, DJVU, EPUB, FB2 and much more, running on Kindle, Kobo, PocketBook and Android devices.


### Miscellaneous
- [MoonScript](http://moonscript.org/) - Moonscript is a dynamic scripting language that compiles to Lua. It reduces verbosity and provides a rich set of features like comprehensions and classes. Its author calls it 'CoffeeScript for Lua'.
- [sitegen](http://leafo.net/sitegen/) - A static site generator which uses MoonScript and supports HTML and Markdown, page grouping, and plugins.


## Resources

### References
- [Reference Manual](http://www.lua.org/manual/5.3/) - The official definition of the Lua language.
- [lua-users wiki](http://lua-users.org/wiki/) - A large community-maintained collection of Lua information and resources, supplementing the official website.
- [Lua Unofficial FAQ](http://www.luafaq.org/) - Answers all sorts of Lua-related questions, including many of the form 'How to ___?'.
- [lua-l](http://www.lua.org/lua-l.html) - The official Lua mailing list, and one of the focal points of the Lua community.

### Glossaries
- [Lua 5.3 Glossary](https://rawgit.com/dlaurie/lua-notes/master/glossary.html) - A glossary of some essential Lua terms.

### Style Guides
- [Lua-users style guide](http://lua-users.org/wiki/LuaStyleGuide) - A general, high-level style guide; unopinionated, easily agreed on.
- [Olivine style guide ★213 ⏳1Y](https://github.com/Olivine-Labs/lua-style-guide) - A more opinionated and specific, and therefore more rigorous, guide.


### Tutorials
- [Lua Crash Course](http://www.coppeliarobotics.com/helpFiles/en/luaCrashCourse.htm) - Short crash course readover, or reference for when you forget the basics.
- [Learn Lua in 15 Minutes](http://tylerneylon.com/a/learn-lua/) - A well-commented example file which covers the basics.
- [Learning Lua from JS](http://phrogz.net/lua/LearningLua_FromJS.html) - An overview of the similarities and differences between Lua and JS; a great start for JavaScript folks looking to pick up Lua.
- [lua-users tutorial](http://lua-users.org/wiki/LuaTutorial) - In-depth collection of tutorials aimed at newcomers.
- [Lua Missions ★218](https://github.com/kikito/lua_missions) - A series of 'Missions' to work through which are designed to teach aspects of Lua along the way.
- [Creating an Image Server](http://leafo.net/posts/creating_an_image_server.html) - Walks through setting up and using OpenResty to build a simple image processing server; a great starting point for playing with OpenResty.


### Articles
- [Embedding Lua in C](http://www.debian-administration.org/articles/264) - An introductory walkthrough of embedding Lua in a C program. A bit dated, but still a great walkthrough.
- [Lua: Good, bad, and ugly parts](http://notebook.kulchenko.com/programming/lua-good-different-bad-and-ugly-parts) - A thorough summary of the good, different, bad, and ugly aspects of Lua, including many subtle quirks, by the author of ZeroBraneStudio.
- [Lua states, libraries, coroutines and memory](http://www.thijsschreijer.nl/blog/?p=693) - Diagrams and explains some more advanced concepts of the Lua VM, particularly when interfacing with C.


### Talks & Slides
- [Roberto's Talks](http://www.inf.puc-rio.br/~roberto/talks/index.html) - History of talks given by Lua's chief architect, with slides for each.
- [Lua Workshop Talks](http://www.lua.org/wshop14.html#abstracts) - High-quality talks are given at each ~annual Lua Workshop, and a history of them is online, slides included.


### Books
- [Programming in Lua](http://www.lua.org/pil/) - The authoritative intro to all aspects of Lua programming, written by Lua's chief architect. Three editions released; first edition available online.
- [Programming Gems](http://www.lua.org/gems/) - A collection of articles covering existing wisdom and practices on programming well in Lua, in a broad variety of use cases.
- [Lua Programming](https://en.wikibooks.org/wiki/Lua_Programming) - A shorter overview of the language, up to date for Lua 5.2, and available online.


### Other Lists
- [awesome-resty ★740](https://github.com/bungle/awesome-resty) - A list like this one, but focused on OpenResty.
- [awesome-love2d](https://github.com/JanWerder/awesome-love2d) - A list like this one, but focused on game dev and the LÖVE platform.
- [awesome-lua ★155 ⏳2Y](https://github.com/forhappy/awesome-lua) by @forhappy - Another list similar to this one. It goes into more depth in a few categories, but has less breadth.
- [Where Lua is Used](https://sites.google.com/site/marbux/home/where-lua-is-used) - A comprehensive list of stand-alone programs written in or extensible using Lua.


## Contribute

Contributions welcome and wanted! Read the [contribution guidelines](https://github.com/LewisJEllis/awesome-lua/blob/master/contributing.md) first.

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, Lewis Ellis has waived all copyright and related or neighboring rights to this work.
---
<p align="center">
	This list is a copy of <a href="http://github.com/LewisJEllis/awesome-lua">LewisJEllis/awesome-lua</a> with ranks
</p>

<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-100705027-1', 'auto');
  ga('send', 'pageview');

</script>