<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="http://github.com/burningtree/awesome-json">burningtree/awesome-json</a> with ranks
</p>
---
# Awesome JSON [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](https://github.com/sindresorhus/awesome)
A curated list of awesome JSON libraries and resources.

Inspired by the [awesome ★59088](https://github.com/sindresorhus/awesome) list.

* [Awesome JSON](#awesome-json)
  * [Applications](#applications)
  * [Binary Serialization](#binary-serialization)
  * [Browser Extensions](#browser-extensions)
  * [Command-line tools](#command-line-tools)
  * [Databases](#databases)
  * [Datasets](#datasets)
  * [Data modeling](#data-modeling)
  * [Data generation](#data-generation)
  * [Differencing](#differencing)
  * [Format Extensions](#format-extensions)
  * [Frontend components](#frontend-components)
  * [Libraries](#libraries)
  * [Linters](#linters)
  * [Online tools](#online-tools)
  * [Schema Specifications](#schema-specifications)
  * [Services](#services)
  * [Supersets](#supersets)
  * [Related formats](#related-formats)
  * [Templates](#templates)
  * [Testing](#testing)
  * [Text Editor Plugins](#text-editor-plugins)
  * [Transformations](#transformations)
  * [Tutorials](#tutorials)
  * [Queries](#queries)
  * [JSON Schema Frontend components](#json-schema-frontend-components)
  * [JSON Schema Tools](#json-schema-tools)
  * [JSON Schema Resources](#json-schema-resources)
  * [JSON Schema Validators](#json-schema-validators)
  * [Contribute](#contribute)

## Applications
**OS X**
* [Visual JSON](https://itunes.apple.com/app/id488709442) ([github ★218 ⏳1Y](https://github.com/youknowone/VisualJSON)) - simple JSON pretty-viewer for Mac OS X.
* [JSONExport ★2593](https://github.com/Ahmed-Ali/JSONExport) - convert a object to a class of one of the currently supported languages.

## Binary Serialization
* [BSON](http://bsonspec.org/) - Binary JSON.
* [MessagePack](http://msgpack.org/) - An extremely efficient object serialization library.
* [UBJSON](http://ubjson.org/) - The universally compatible format specification for binary JSON.
* [CBOR](https://tools.ietf.org/html/rfc7049) - Concise Binary Object Representation.
* [Smile](http://wiki.fasterxml.com/SmileFormatSpec) - A efficient binary data format.
* [PSON ★227 ⏳2Y](https://github.com/dcodeIO/PSON) - Protocol JSON, super efficient binary serialization format.

## Browser Extensions
**Chrome**
* [JSON Formatter](https://chrome.google.com/webstore/detail/json-formatter/bcjindcccaagfpapjjmafapmmgkkhgoa) ([github ★948](https://github.com/callumlocke/json-formatter)) - Makes JSON easy to read. Open source.
* [JSON Viewer](https://chrome.google.com/webstore/detail/json-viewer/gbmdgpbipfallnflgajpaliibnhdgobh) ([github ★589](https://github.com/tulios/json-viewer)) - It is a Chrome extension for printing JSON and JSONP.
* [JSON Browser](https://chrome.google.com/webstore/detail/json-browser/hngfgkmimoikmpohakflgadcajkfnoba) ([github ★10 ⏳3Y](https://github.com/platy/json-browser)) - Browse a JSON web with the help of JSON schemas.
* [JSON Finder](https://chrome.google.com/webstore/detail/json-finder/flhdcaebggmmpnnaljiajhihdfconkbj) ([github ★24](https://github.com/rapee/jsonfinder)) - Browse like you do it in Finder.

**Firefox**
* [JSONView](https://addons.mozilla.org/en-US/firefox/addon/jsonview/) ([github ★635](https://github.com/bhollis/jsonview)) - View JSON documents in the browser.
* [JSON-DataView](https://addons.mozilla.org/en-us/firefox/addon/json-dataview/) ([github ★10 ⏳2Y](https://github.com/warren-bank/moz-json-data-view)) - Displays data in a collapsible tree structure with syntax highlights.

**Safari**
* [JSONAce](https://safari-extensions.apple.com/details/?id=com.acrogenesis.jsonace-56Q494QF3L) ([github ★57](https://github.com/acrogenesis/JSONAce)) - Formats & syntax highlights JSON viewed inside of the web browser using the ACE editor.
* [JSONView](https://safari-extensions.apple.com/details/?id=com.acrogenesis.jsonview-56Q494QF3L) ([github ★241 ⏳1Y](https://github.com/acrogenesis/jsonview-safari)) - A port of the JSONView Firefox extension that formats and syntax highlights JSON viewed inside of the browser

## Command-line tools
* [jsoncat ★11](https://github.com/pantuza/jsoncat) - Pretty-print Json in terminal with colors and adjusting tabs size.
* [jq](http://stedolan.github.io/jq/) - A lightweight and flexible command-line JSON processor.
* [json](http://trentm.com/json/) - A "json" command for massaging JSON on your Unix command line.
* [jshon](http://kmkeen.com/jshon/) - A parser designed for maximum convenience within the shell.
* [jarg](http://jdp.github.io/jarg/) - Shorthand JSON and form encoding syntax in the shell.
* [jsawk ★1201](https://github.com/micha/jsawk) - Like awk, but for JSON.
* [gron ★640](https://github.com/tomnomnom/gron) - Convert a JSON file into discrete assignments that are greppable.
* [jid ★4116](https://github.com/simeji/jid) - Incremental Digger. Drill down JSON interactively by using filtering queries like jq.

## Databases
* [MongoDB](https://www.mongodb.com/) - an open-source document database, and the leading NoSQL database.
* [RethinkDB](https://rethinkdb.com/) - An open-source distributed document database with a pleasant and powerful query language.
* [EJDB](http://ejdb.org/) - Embedded JSON Database engine. (C)
* [lowdb ★4629](https://github.com/typicode/lowdb) - Flat file database built on lodash API. (Javascript)
* [Lawnchair](http://brian.io/lawnchair/) - A lightweight clientside document store. (Javascript)
* [JSON ODM ★45](https://github.com/konsultaner/jsonOdm) - Object document mapper for JavaScript to use on the server or in the browser. (Javascript)
* [JSON Server ★21775](https://github.com/typicode/json-server) - Get a full fake REST API with zero coding in less than 30 seconds.
* [Kinto ★3144](https://github.com/Kinto/kinto) - A lightweight JSON storage service with synchronisation and sharing abilities.
* [CouchDB](http://couchdb.apache.org/) - Seamless multi-master sync, that scales from Big Data to Mobile, with an Intuitive HTTP/JSON API and designed for Reliability.
* [JSONlite ★797](https://github.com/nodesocket/jsonlite) - A simple, self-contained, serverless, zero-configuration, json document store. (Bash)

## Datasets
* [countries ★3080](https://github.com/mledoze/countries) - World countries.
* [vat-rates](http://jsonvat.com/) - VAT rates for all EU countries.
* [MTG JSON](http://mtgjson.com/) - Up to date Magic the Gathering card data.
* [Heartstone JSON](https://hearthstonejson.com/) - Up to date Hearthstone card data.
* [getCountries()](http://peric.github.io/GetCountries/) - Generator for custom Countries data.

## Data modeling
* [JSONModel](https://github.com/jsonmodel/jsonmodel ) - Magical Data Modelling Framework. (Objective-C)

## Data generation
* [jsonymize ★8 ⏳1Y](https://github.com/cameronhunter/jsonymize) - Reads data from standard input, anonymizes, then writes to standard output.
* [dyson ★612](https://github.com/webpro/dyson) - Server for dynamic, fake JSON. (node.js)

## Differencing
* [JSONPatch](http://jsonpatch.com/) - A format for describing changes to a document.
* [JSON-Patch ★590](https://github.com/Starcounter-Jack/JSON-Patch) - Lean and mean Javascript implementation of the JSON-Patch standard (RFC 6902). (Javascript)
* [jiff ★282](https://github.com/cujojs/jiff) - JSON Patch and diff based on rfc6902. (Javascript)
* [json-patch-php ★56](https://github.com/mikemccabe/json-patch-php) - implementation of JSON-patch (IETF RFC 6902) (PHP)
* [dffptch ★157](https://github.com/paldepind/dffptch) - A micro library for diffing and patching using a compact diff format. (Javascript)
* [jsondiffpatch ★1981](https://github.com/benjamine/jsondiffpatch) - Diff & patch for JavaScript objects. (Javascript)

## Editors
* [JSONEdit](http://mb21.github.io/JSONedit/) - User friendly, visual editor built as an AngularJS directive.

## Format Extensions
* [GeoJSON](http://geojson.org/) - A geospatial data interchange format.
* [JSON-LD](http://json-ld.org/) - A lightweight Linked Data format.
* [JSON-RPC](http://www.jsonrpc.org/) - A stateless, light-weight remote procedure call (RPC) protocol.
* [JSONP](http://www.json-p.org/) - Safer cross-domain Ajax with JSON-P/JSONP.
* [JsonML](http://www.jsonml.org/) - A compact format for transporting XML-based markup as JSON which allows it to be losslessly converted back to its original form.
* [JSON5](http://json5.org/) - a extension that aims to make it easier for humans to write and maintain by hand.
* [JSON Resume](https://jsonresume.org/) - The open source initiative to create standard for resumes.
* [JSON Web Tokens](https://jwt.io/) - A compact URL-safe means of representing claims to be transferred between two parties.
* [JSON API](http://jsonapi.org/) - A standard for building APIs.
* [Collection+JSON](http://amundsen.com/media-types/collection/) - A read/write hypermedia-type designed to support management and querying of simple collections.
* [hal-json](http://stateless.co/hal_specification.html) - A set of conventions for expressing hyperlinks in either JSON or XML.
* [JSON Activity Streams](http://activitystrea.ms/) - A format for syndicating social activities around the web.
* [JSON-stat ★12](https://github.com/jsonstat/jsonstat) - Simple lightweight format for data dissemination.
* [/contribute.json](https://www.contributejson.org/) - Making open source contribution information easier to access, across projects.
* [JSON Table Schema](http://frictionlessdata.io/guides/json-table-schema/) - a simple schema for tabular data
* [NDJSON](http://ndjson.org/) (Newline delimited JSON) - a standard for delimiting JSON in stream protocols.
* [survey.js](http://surveyjs.org/) - JSON based survey library.

## Frontend components
* [JSON editor jQuery plugin ★433 ⏳3Y](https://github.com/DavidDurman/FlexiJsonEditor) - component for you web apps/pages. (jQuery)
* [jqTree](http://mbraak.github.io/jqTree/) - Widget for displaying a tree structure in html. (jQuery)
* [jsTree](https://www.jstree.com/docs/json/) - jquery plugin, that provides interactive trees. (jQuery)
* [Dynatable.js](https://www.dynatable.com/) - A funner, semantic, HTML5+JSON, interactive table plugin. (jQuery)
* [JSON Formatter ★305](https://github.com/mohsen1/json-formatter) - Angular directive for collapsible JSON in HTML. (AngularJS)

## Libraries
**C**
* [Jansson](http://www.digip.org/jansson/) - A C library for encoding, decoding and manipulating data.
* [jsmn](http://zserge.com/jsmn.html) - A minimalistic parser in C. It can be easily integrated into the resource-limited projects or embedded systems.

**C++**
* [ArduinoJson ★1918](https://github.com/bblanchon/ArduinoJson) - An efficient library for embedded systems.
* [JSON++ ★32 ⏳1Y](https://github.com/tunnuz/json) - A self contained Flex/Bison parser for C++11.
* [json11 ★1301](https://github.com/dropbox/json11) - A tiny library for C++11.
* [RapidJSON ★4373](https://github.com/miloyip/rapidjson) - A fast JSON parser/generator for C++ with both SAX/DOM style API

**Clojure**
* [data.json ★294](https://github.com/clojure/data.json) - parser/generator to/from Clojure data structures.

**Fortran**
* [JSON-Fortran ★75](https://github.com/jacobwilliams/json-fortran) - A Fortran library for writing, reading, and manipulating JSON files and data structures.

**Haskell**
* [aeson-qq ★34 ⏳1Y](https://github.com/sol/aeson-qq) - JSON quasiquoter for Haskell.

**Java**
* [JSON-java ★2431](https://github.com/stleary/JSON-java) - A reference implementation.
* [Fast JSON Processor ★9209](https://github.com/alibaba/fastjson)
* [Gson ★8856](https://github.com/google/gson) - A Java library to convert JSON to Java objects and vice-versa.
* [Jackson](http://wiki.fasterxml.com/JacksonHome) - A multi-purpose Java library for processing JSON data format.
* [moshi ★2784](https://github.com/square/moshi) - A modern JSON library for Android and Java.

**Javascript**
* [JSON-js ★6872](https://github.com/douglascrockford/JSON-js) - JSON in JavaScript.
* [JSON 3](http://bestiejs.github.io/json3/) - A modern implementation.
* [oboe.js](https://oboejs.com/) - A streaming approach, speeds up web applications by providing parsed objects before the response completes.

**Objective-C**
* [JSONKit ★6093 ⏳1Y](https://github.com/johnezang/JSONKit) - Objective-C library.
* [SBJson](http://www.sbjson.org/) - Parse one or more chunks of data.

**Perl**
* [JSON::Tiny ★10](https://github.com/daoswald/JSON-Tiny) - Perl module for encoding and decoding JSON in a minimalistic way.

**PL/SQL**
* [PL/JSON ★143](https://github.com/pljson/pljson) - A generic JSON object written in PL/SQL.

**PHP**
* [Webmozart JSON ★311](https://github.com/webmozart/json) - A robust decoder/encoder with support for schema validation.

**Python**
* [simplejson ★819](https://github.com/simplejson/simplejson) - A simple, fast, extensible encoder/decoder
* [jsonpickle](http://jsonpickle.github.io/) - Library for serializing any arbitrary object graph.
* [metamagic.json](https://pypi.python.org/pypi/metamagic.json/0.9.6) - An ultra-fast Python 3 implementation of a JSON encoder.

**Ruby**
* [oj ★1760](https://github.com/ohler55/oj) - A fast JSON parser and Object marshaller as a Ruby gem.
* [MultiJSON ★565](https://github.com/intridea/multi_json) - A generic swappable back-end for JSON handling.

**React**
* [json2react ★122](https://github.com/txgruppi/json2react) - Use JSON to create React Stateless Components.

**.NET**
* [jsonfx ★338](https://github.com/jsonfx/jsonfx) - serialization framework for .NET.

**Scala**
* [spray-json ★620](https://github.com/spray/spray-json) - A lightweight, clean and simple implementation in Scala.
* [circe ★882](https://github.com/circe/circe) - Yet another JSON library for Scala.
* [scala-jsonapi ★89](https://github.com/zalando/scala-jsonapi) - Support library for integrating the JSON:API spec with Play, Spray and/or Circe backends.

**Swift**
* [SwiftyJSON ★14542](https://github.com/SwiftyJSON/SwiftyJSON) - The better way to deal with data in Swift.

## Linters
* [jsonlint ★1067](https://github.com/zaach/jsonlint) - Parser and validator with a CLI. (Javascript)
* [JSON Lint ★234](https://github.com/Seldaek/jsonlint) - PHP linter. (PHP)

## Online tools
* [JSON Data Ninja](http://www.jsondata.ninja) - The most productive way to visualize and explore tabular JSON data.
* [JSONLint Pro](http://pro.jsonlint.com/) - The JSON Validator.
* [JSONMate](http://jsonmate.com/) - JSON editor, inspector and beautifier.
* [JSON Editor online](http://jsoneditoronline.org/) - A web-based tool to view, edit and format.
* [Collapsible JSON Formatter](http://www.bodurov.com/JsonFormatter/) - Formatter and Colorer of Raw Code.
* [JSON Formatter and Validator](https://jsonformatter.curiousconcept.com/) - Formatter to help with debugging.
* [JSON Generator](http://www.json-generator.com/) - Tool for generating random data.
* [JSON to CSV](http://konklone.io/json/) - A free, in-browser JSON to CSV converter.
* [json2csharp](http://json2csharp.com/) - Generate c# classes from a json string or url.
* [JSON Utils](http://jsonutils.com/) - Site for generating C#, VB.Net, and Javascript classes from JSON.
* [geojson.io](http://geojson.io/) - Simply edit GeoJSON map data.
* [jq play](https://jqplay.org/) - A playground for jq.
* [json2yaml](https://www.json2yaml.com/) - Convert JSON to YAML online.
* [JSON Selector Generator](http://jsonselector.com/) - A simple GUI for generating the selectors to access.
* [JSON.fr](https://www.json.fr/) - Fully client-side validator and formatter.
* [ObjGen](http://www.objgen.com/json) - Online live JSON generator.
* [JsonStub](https://jsonstub.com/) - Online JSON faker.
* [JSONPlaceholder](https://jsonplaceholder.typicode.com/) - Fake Online REST API for Testing and Prototyping.

## Schema Specifications
* [JSON Schema](http://json-schema.org/) - a JSON based format for defining the structure of JSON data.
* [Itemscript](http://itemscript.org/ItemscriptSchema.html) - Language for validating and specifying values.
* [Kwalify](http://www.kuwata-lab.com/kwalify/) - A parser, schema validator, and data binding tool
* [Rx](http://rx.codesimply.com/) - Simple, Extensible Schemata.

## Services
* [JSONProxy](http://jsonp.afeld.me/) - Simple HTTP proxy that enables cross-domain requests to any JSON API.
* [Myjson](http://myjson.com/) - A simple store for your web or mobile app.
* [Telize](http://www.telize.com/) - JSON IP and GeoIP REST API.
* [jsonpad](https://jsonpad.io/) - a simple JSON storage platform.
* [JSONP Proxy ★8](https://github.com/fcambus/jsonp-proxy) - A REST API allowing to get JSONP from any API.

## Supersets
* [YAML](http://yaml.org) - A human friendly data serialization standard for all programming languages.
* [HanSON ★112](https://github.com/timjansen/hanson) - JSON for Humans - with unquoted identifiers, multi-line strings and comments.
* [μson ★54 ⏳1Y](https://github.com/burningtree/uson) (uson) - a shorthand for JSON.
* [HOCON](https://github.com/typesafehub/config/blob/master/HOCON.md#hocon-human-optimized-config-object-notation) - Human-Optimized Config Object Notation.
* [ASON](http://www.americanteeth.org/libason/ason_spec.pdf) - A semantically complete superset of JSON (draft).
* [TOML ★5914](https://github.com/toml-lang/toml) - A minimal configuration file format that's easy to read due to obvious semantics.
* [HCL ★1019](https://github.com/hashicorp/hcl) - A structured configuration language that is both human and machine friendly.

## Tutorials
* [Introducing JSON](http://json.org/)
* [JSON Tutorial](http://www.w3resource.com/JSON/introduction.php) - An introductory tutorial on JavaScript Object Notation (JSON).
* [JSON - Rosetta Code](http://rosettacode.org/wiki/JSON) - Basic operations in different languages (57 languages in this moment).
* [What is JSON and how to use it](https://ilovecoding.org/lessons/json-what-is-json-and-how-to-use-it) - Video tutorial for beginners.
* [jq Primer: Munging JSON Data](http://andrew.gibiansky.com/) - How jq can be used to process JSON files just as effectively as traditional Unix tools.

## Related formats
* [AXON](https://intellimath.bitbucket.io/axon/) - A simple text based format for interchanging of objects, documents and data. It tries to combine the best of JSON, XML and YAML.
* [CSON ★1023](https://github.com/bevry/cson) - CoffeeScript-Object-Notation. JSON for CoffeeScript objects.
* [MSON ★582](https://github.com/apiaryio/mson) - Markdown syntax compatible with describing JSON and JSON Schema.
* [ArchieML](http://archieml.org/) - Structured text format optimized for human writability.


## Templates
* [Jsonnet](http://jsonnet.org/) - A domain specific configuration language that helps you define JSON data.
* [rabl ★3469](https://github.com/nesquena/rabl) - General ruby templating with json, bson, xml, plist and msgpack support. (Ruby)
* [json2html](http://json2html.com/) - HTML templating library with wrappers for both jQuery and Node.js. (Javascript)

## Testing
* [JSON Test](http://www.jsontest.com/) - Testing platform for services utilizing JavaScript Object Notation (JSON).
* [JSONassert ★362](https://github.com/skyscreamer/JSONassert) - Write JSON unit tests in less code. Great for testing REST interfaces. (Java)
* [JsonUnit ★196](https://github.com/lukas-krecan/JsonUnit) - A library that simplifies JSON comparison in unit tests. It's strongly inspired by XmlUnit.

## Text Editor Plugins
**Emacs**
* [JSON Reformat ★116](https://github.com/gongo/json-reformat) - Reformat tool.

**Vim**
* [vim-json ★814](https://github.com/elzr/vim-json) - A better JSON for Vim: distinct highlighting of keywords vs values, JSON-specific (non-JS) warnings, quote concealing. Pathogen-friendly.

## Transformations
* [json-sharp ★4 ⏳1Y](https://github.com/globocom/json-sharp) - Javascript tool to process operations on pure JSON objects. (Javascript)
* [json2json ★145 ⏳1Y](https://github.com/joelvh/json2json) - Transform (reformat) structures from one to another. (Javascript)
* [trans ★175 ⏳1Y](https://github.com/gabesoft/trans) - The ultimate object transformer. (Javascript)
* [osmtogeojson ★234](https://github.com/tyrasd/osmtogeojson) - Converts OSM data to GeoJSON. (Javascript)
* [x2js ★457](https://github.com/abdmob/x2js) - XML to JSON and vice versa javascript conversion functions. (Javascript)
* [JSONC ★369](https://github.com/tcorral/JSONC) - JSON compressor and decompressor. (Javascript)
* [JsonMapper ★554](https://github.com/cweiske/jsonmapper) - Map nested structures onto PHP classes (PHP)
* [SassyJSON ★171](https://github.com/HugoGiraudel/SassyJSON) - Sass-powered API. (Sass)
* [json.human.js](http://marianoguerra.github.io/json.human.js/) - A small library to convert a JSON object into a human readable HTML representation that is easy to style for different purposes.
* [JSONtoFoundation ★42 ⏳2Y](https://github.com/fmscode/JSONtoFoundation) - OS X utility that converts a JSON object to a Foundation object that can be used in Cocoa/Cocoa Touch development. (Swift)
* [fanci ★15 ⏳1Y](https://github.com/liip/fanci) - Extract, rename and transform JSON based on a template. (node.js)
* [Pinch ★22 ⏳2Y](https://github.com/Baggz/Pinch) - String.replace for JavaScript objects. (Javascript)
* [deepjson](http://deepjson.jacoborus.codes/) - A better way to load big json config files. (node.js)
* [jsontl ★4 ⏳2Y](https://github.com/DoublePrecisionSoftware/jsontl) - allow transformation using a JSON-based transformation language. (node.js)
* [json-transforms ★18](https://github.com/ColinEberhardt/json-transforms) - A recursive, pattern-matching, approach to transforming JSON structures.
* [normalizr ★8409](https://github.com/paularmstrong/normalizr) - Normalizes nested JSON according to a schema. (Javascript)

## Queries
* [JMESPath](http://jmespath.org/) - A query language for JSON.
* [JSON Mask ★455](https://github.com/nemtsov/json-mask) - Tiny language and engine for selecting specific parts of a JS object, hiding the rest. (Javascript)
* [JSONiq](http://www.jsoniq.org/) - The JSON Query Language.
* [ObjectPath](http://objectpath.org/) - The agile query language for semi-structured data. (Python)
* [DefiantJS](http://www.defiantjs.com/) - Lightning-fast searches using XPath expressions, and transform using XSL. (Javascript)
* [JSONSelect ★1568](https://github.com/lloyd/JSONSelect) - CSS-like selectors. (Javascript)
* [JSONPath](http://goessner.net/articles/JsonPath/) - XPath implementation. (Javascript/PHP)
* [searchjs ★133](https://github.com/deitch/searchjs) - A library for filtering based on a json SQL-like language.
* [json-rel ★7](https://github.com/slurmulon/json-where) - Transparent references in JSON.

## JSON Schema Frontend components
* [JSON Editor ★3883](https://github.com/jdorn/json-editor) - JSON Schema Based Editor. (jQuery)
* [angular-schema-form ★1947](https://github.com/json-schema-form/angular-schema-form) - Generate forms. (AngularJS)
* [JSON Schema View ★30](https://github.com/mohsen1/json-schema-view) - An AngularJS directive for rendering JSON Schema in HTML (AngularJS)
* [Angular JSON Schema Form ★19](https://github.com/mohsen1/angular-json-schema-form) - Angular directive for making forms out of JSON Schema. (AngularJS)
* [AlpacaJS](http://www.alpacajs.org) - Generates JSON Schema driven forms on top of Bootstrap, jQuery Mobile, jQuery UI and HTML (jQuery)


## JSON Schema Tools
* [prmd ★1723](https://github.com/interagent/prmd) - Tools and doc generation for HTTP APIs.
* [generate-schema ★331](https://github.com/Nijikokun/generate-schema) - Effortlessly convert your JSON Object to JSON Schema, Mongoose Schema, or a Generic template for quick documentation / upstart.
* [Docson ★331](https://github.com/lbovet/docson) - Documentation for your types.
* [Orderly JSON ★185 ⏳7Y](https://github.com/lloyd/orderly) - A textual format for describing JSON compiled into JSONSchema.
* [jsonschema2pojo ★2814](https://github.com/joelittlejohn/jsonschema2pojo) - Generates Java types and annotates those types for data-binding with Jackson 1.x or 2.x, Gson, etc.
* [Matic ★151](https://github.com/mattyod/matic) - Build tool for generating HTML documentation.
* [JSON Schema + Faker ★802](https://github.com/json-schema-faker/json-schema-faker) - Fake your schemas.
* [DLL.js ★50](https://github.com/moll/js-ddl) - Gets you a JSON Schema from PostgreSQL or SQLite3.
* [JSONSchema.net](https://jsonschema.net//) - JSON Schema generator from JSON object.
* [js-schema ★329](https://github.com/molnarg/js-schema) - A new way of describing object schemas in JavaScript. It has a clean and simple syntax, and it is capable of serializing to/from the popular JSON Schema format.

## JSON Schema Resources
* [Understanding JSON Schema](https://spacetelescope.github.io/understanding-json-schema/) - A website aiming to provide more accessible documentation for JSON schema.
* [JSON Schema Store](http://schemastore.org/json/) - A collection of popular schemas.
* [JSON Archetypes ★131 ⏳1Y](https://github.com/servant-app/json-archetypes) - Community-Driven Standards For Popular Types Of Data.
* [Using JSON Schema](http://usingjsonschema.com/) - a Book and GitHub project, showing how JSON Schema can be used for a variety of tasks and in different programming contexts.

## JSON Schema Validators
**Javascript and Node.js**
* [json-schema-benchmark ★190](https://github.com/ebdrup/json-schema-benchmark) - Performance benchmark for Node.js validators.
* [is-my-json-valid ★683](https://github.com/mafintosh/is-my-json-valid) - A validator that uses code generation to be extremely fast.
* [jsen ★118](https://github.com/bugventure/jsen) - A validator built for speed.
* [themis ★57 ⏳1Y](https://github.com/playlyfe/themis) - A blazing fast validator.
* [jsck ★161](https://github.com/pandastrike/jsck) - JSON Schema Compiled checK.
* [z-schema ★222](https://github.com/zaggino/z-schema) - validator written in JavaScript for NodeJS and Browsers.
* [jjv ★179](https://github.com/acornejo/jjv) - Javascript Library for Schema Validation.
* [request-validator ★0 ⏳2Y](https://github.com/bugventure/request-validator) - Flexible request validator middleware for express and connect.
* [tv4 ★865](https://github.com/geraintluff/tv4) - Tiny Validator.
* [ajv ★1718](https://github.com/epoberezkin/ajv) - The fastest validator. Supports v5/6 proposals.


**PHP**
* [JSON Schema for PHP ★921](https://github.com/justinrainbow/json-schema) - PHP implementation of JSON schema.
* [JSON Guard](http://json-guard.thephpleague.com) - A validator for JSON Schema Draft 4.

**Python**
* [jsonschema ★1179](https://github.com/Julian/jsonschema) - Python implementation of jsonschema.
* [JSON Schema Toolkit ★25 ⏳1Y](https://github.com/petrounias/json-schema-toolkit) - Programmatic building of JSON schemas (recursive field mappings) with validation, a Django JSON Field, and native PostgreSQL JSON type constraints.

**Ruby**
* [Ruby JSON Schema Validator ★846](https://github.com/ruby-json-schema/json-schema) - validating against a JSON schema conforming to JSON Schema Draft 4.

## Contribute
Contributions welcome! Read the [contribution guidelines](https://github.com/burningtree/awesome-json/blob/master/CONTRIBUTING.md) first.

## License
[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
---
<p align="center">
	This list is a copy of <a href="http://github.com/burningtree/awesome-json">burningtree/awesome-json</a> with ranks
</p>

<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-100705027-1', 'auto');
  ga('send', 'pageview');

</script>