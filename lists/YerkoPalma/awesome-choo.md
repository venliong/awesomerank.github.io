<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="http://github.com/YerkoPalma/awesome-choo">YerkoPalma/awesome-choo</a> with ranks
</p>
---
# Awesome choo [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](https://github.com/sindresorhus/awesome) <div align="right">:steam_locomotive::train::train::train::train::train:</div>

> [choo](https://choo.io/) is a `5kb` framework for creating
> sturdy frontend applications

## Contents

- [Official resources](#official-resources)
- [Dependencies](#dependencies)
- [Demos](#demos)
- [Community](#community)
- [Plugins and addons](#plugins-and-addons)
- [Elements](#elements)
- [CLI Templates](#cli-templates)
- [Resources](#resources)
- [Projects using choo](#projects-using-choo)

### Official resources

- [Docs](https://github.com/yoshuawuyts/choo/blob/master/README.md)
- [Handbook ★138](https://github.com/yoshuawuyts/choo-handbook)
- [Repo ★3811](https://github.com/yoshuawuyts/choo)
- [Website](https://choo.io/)
- [Twitter thread](https://twitter.com/yoshuawuyts/status/730087077803528193)

### Dependencies
`choo` is a modular framework. These are the dependencies it glues together
under the hood:

- [yo-yo ★1075](https://github.com/maxogden/yo-yo) - Modular UI library using DOM
  diffing and ES6 template strings.
- [bel ★302](https://github.com/shama/bel) - Create composable DOM elements using
  template strings.
- [hyperx ★690](https://github.com/substack/hyperx) - Convert template strings to
  library backends.
- [morphdom ★1238](https://github.com/patrick-steele-idem/morphdom) - Fast and
  lightweight DOM diffing/patching (without the virtual part).
- [nanoraf ★41](https://github.com/yoshuawuyts/nanoraf) - Only call RAF when needed.
- [barracks ★167](https://github.com/yoshuawuyts/barracks) - Action dispatcher for
  unidirectional data flows.
- [sheet-router ★180](https://github.com/yoshuawuyts/sheet-router) - Fast, modular
  client-side router.

### Demos

- [Input example](http://requirebin.com/?gist=e589473373b3100a6ace29f7bbee3186) - ([repo](https://github.com/yoshuawuyts/choo/tree/master/examples/title))
- [HTTP effects](https://hyperdev.com/#!/project/fork-fang)
- [Mailbox routing](https://github.com/yoshuawuyts/choo/tree/master/examples/mailbox)
- [TodoMVC](http://shuheikagawa.com/todomvc-choo) - ([repo ★35](https://github.com/shuhei/todomvc-choo))
- [choo-firebase](https://choo-firebase-2ec21.firebaseapp.com) - ([repo](https://github.com/mw222rs/choo-firebase))
- [Grow](https://grow.static.land) - ([repo ★15](https://github.com/sethvincent/grow))
- [Chatbot](http://chootbot.herokuapp.com) - ([repo ★1](https://github.com/plaey/chatbot))
- [chat-random ★3](https://github.com/akiva/chat-random)
- [choo-leaflet-demo ★12](https://github.com/timwis/choo-leaflet-demo)

### Community

- [Freenode](https://webchat.freenode.net/?channels=choo)

### Plugins and addons

- [choo-location-electron](https://github.com/bcomnes/choo-location-electron) - Fix `choo`'s router in electron.
- [choo-log ★38](https://github.com/yoshuawuyts/choo-log) - Development logger for choo.
- [choo-test ★16](https://github.com/mantoni/choo-test) - Easy choo app unit testing.
- [choo-persist ★29](https://github.com/yoshuawuyts/choo-persist) - Synchronize choo state with indexedDB.
- [choo-promise ★1](https://github.com/rahatarmanahmed/choo-promise) - Use promises in effects and subscriptions.
- [choo-pull ★12](https://github.com/yoshuawuyts/choo-pull) - Wrap handlers to use pull-stream in a choo plugin.
- [choo-redirect ★10](https://github.com/yoshuawuyts/choo-redirect) - Redirect a view to another view.
- [choo-model ★9](https://github.com/yoshuawuyts/choo-model) - Experimental state management lib for choo.
- [choo-resume ★12](https://github.com/bengourley/choo-resume) - choo-resume + hot-rld = hot app reload in choo.

### Elements

- [dom-notifications ★100](https://github.com/finnp/dom-notifications) - Atom-inspired notifications component.
- [choodown ★13](https://github.com/trainyard/choodown) - A simple markdown component for choo.
- [choo-md-editor ★1](https://github.com/dbtek/choo-md-editor) - Lightweight markdown editor that can be used inside Choo app or as a standalone library.
- [choo-chartist ★7](https://github.com/rexmortus/choo-chartist) - A little component for using [Chartist](https://gionkunz.github.io/chartist-js/) with the choo framework.

### CLI Templates

Templates for [choo-cli ★51](https://github.com/trainyard/choo-cli)

- [trainyard/template-basic ★1](https://github.com/trainyard/template-basic)
- [haroenv/template-webpack ★3](https://github.com/haroenv/template-webpack)

### Resources
> :movie_camera: : videos
> :computer: : tutorials
> :book: : articles

- :computer: [Your first choo app](https://yoshuawuyts.gitbooks.io/choo/content/02_your_first_app.html)
- :movie_camera: [TCBY community live hangout](https://www.youtube.com/watch?v=a97Mw2z1SAI)
- :book: [A better frontend experience](https://medium.com/@yoshuawuyts/a-better-frontend-experience-7b0498c85658)
- :book: [Composition in CycleJS, choo, React and Angular2](http://blog.krawaller.se/posts/composition-in-cyclejs-choo-react-and-angular2)
- :book: [Stupidly smart components in choo](http://blog.krawaller.se/posts/stupidly-smart-components-in-choo)

### Projects using choo

- [boxcar ★9](https://github.com/toddself/boxcar) - A choo-based grid/spreadsheet editor.
- [choo-sortable ★2](https://github.com/willkessler/choo-sortable) - Building sortable code with choo.
- [hacker-choo](https://github.com/mw222rs/hacker-choo) - Hacker Typer clone written in choo.
- [footprint-rechoo](https://github.com/npeihl/footprint-rechoo) - A choo rewrite of [footprint-review](http://github.com/sjcgis/footprint-review).
- [minidocs ★116](https://github.com/freeman-lab/minidocs) – A documentation site generator built with choo.
- [dataface ★11](https://github.com/timwis/dataface) - Desktop application to manage databases.
- [BlankUp ★29](https://github.com/HoverBaum/BlankUp-Electron) - Multiplatform markdown editor.
- [hackernews-choo ★27](https://github.com/kvnneff/hackernews-choo) - A Hacker News reader built with choo.
- [tic-tac-choo ★5](https://github.com/YerkoPalma/tic-tac-toe) - Progressive tic tac toe game, made with choo.
- [enviar ★28](https://github.com/timwis/enviar) - Chat interface for SMS / text messages.
- [kaktus ★328](https://github.com/kaktus/kaktus) - A new minimalistic web browser, built on `choo` and IndexedDB.
- [civicdr.org ★2](https://github.com/CiviCDR/civicdr.org) - Website for [CiviCDR](https://civicdr.org/).
- [nekocafe ★11](https://github.com/notenoughneon/nekocafe) - Web chat room :cat: :speech_balloon:.

### License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Yerko Palma](https://github.com/YerkoPalma) has waived all copyright and related or neighboring rights to this work.
---
<p align="center">
	This list is a copy of <a href="http://github.com/YerkoPalma/awesome-choo">YerkoPalma/awesome-choo</a> with ranks
</p>

<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-100705027-1', 'auto');
  ga('send', 'pageview');

</script>