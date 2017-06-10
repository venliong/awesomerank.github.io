<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="http://github.com/eleventigers/awesome-rxjava">eleventigers/awesome-rxjava</a> with ranks
</p>
---
# Awesome RxJava [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](https://github.com/sindresorhus/awesome)

[<img src="http://reactivex.io/assets/Rx_Logo_S.png" align="right" width="100">](http://reactivex.io/)

> Useful resources for working with [RxJava ★24565](https://github.com/ReactiveX/RxJava)

*Inspired by the [awesome ★59088](https://github.com/sindresorhus/awesome) list thing.*

## Bindings

* [RxAndroid ★12490](https://github.com/ReactiveX/RxAndroid) - Android specific bindings for RxJava.
* [RxBinding ★5537](https://github.com/JakeWharton/RxBinding) - RxJava binding APIs for Android UI widgets from the platform and support libraries.
* [rx-preferences ★1112](https://github.com/f2prateek/rx-preferences) - Reactive `SharedPreferences` for Android.
* [RxPermissions ★3636](https://github.com/tbruyelle/RxPermissions) - Android M runtime permissions powered by RxJava.
* [SQLBrite ★3949](https://github.com/square/sqlbrite) - A lightweight wrapper around SQLiteOpenHelper and ContentResolver which introduces reactive stream semantics to queries.
* [Android-ReactiveLocation ★1717](https://github.com/mcharmas/Android-ReactiveLocation) - Small library that wraps Google Play Service API in brilliant RxJava Observables reducing boilerplate to minimum.
* [ReactiveNetwork ★927](https://github.com/pwittchen/ReactiveNetwork) - Android library listening network connection state and change of the WiFi signal strength with RxJava Observables.
* [ReactiveSensors ★103](https://github.com/pwittchen/ReactiveSensors) - Android library monitoring hardware sensors with RxJava Observables.
* [RxPalette ★191](https://github.com/hzsweers/RxPalette) - RxJava bindings for the Palette library on Android.
* [rxjava-jdbc ★504](https://github.com/davidmoten/rxjava-jdbc) - Efficient execution and functional composition of database calls using jdbc and RxJava Observables.
* [rxjava-file ★56](https://github.com/davidmoten/rxjava-file) - RxJava observables for files including NIO events.
* [RxTuples ★116](https://github.com/pakoito/RxTuples) - Simple tuples to use with RxJava.
* [RxAnimationBinding ★74 ⏳1Y](https://github.com/blipinsk/RxAnimationBinding) - RxJava binding APIs for Android's animations.

## Utilities
* [RxJavaAsyncUtil ★98](https://github.com/ReactiveX/RxJavaAsyncUtil) - Async utilities for RxJava.
* [RxJavaJoins ★75 ⏳2Y](https://github.com/ReactiveX/RxJavaJoins) - Joins operators for RxJava.
* [RxJavaMath ★78](https://github.com/ReactiveX/RxJavaMath) - Math operators for RxJava.
* [RxJavaString ★107](https://github.com/ReactiveX/RxJavaString) - 
String and Byte operators for RxJava.
* [RxJavaComputationExpressions ★51 ⏳1Y](https://github.com/ReactiveX/RxJavaComputationExpressions) - Computation expressions for RxJava.
* [rxjava-extras ★212](https://github.com/davidmoten/rxjava-extras) - Utilities for use with RxJava.
* [RxActions ★34](https://github.com/pakoito/RxActions) - Simple ActionN composition to use with RxJava.
* [RxRelay ★1222](https://github.com/JakeWharton/RxRelay) - RxJava types that are both an Observable and an Action1.
* [Frodo ★1191](https://github.com/android10/frodo) - Android Library for Logging RxJava Observables and Subscribers.
* [RxPartialApplication ★32](https://github.com/pakoito/RxPartialApplication) - Simple partial application for FuncN and ActionN on RxJava.
* [RxCurrying ★39](https://github.com/pakoito/RxCurrying) - Simple currying for FuncN and ActionN on RxJava.
* [RxEither ★78 ⏳1Y](https://github.com/eleventigers/rxeither) - Either type for RxJava.
* [RxReplayingShare ★343](https://github.com/JakeWharton/RxReplayingShare) - An RxJava transformer which combines replay(1), publish(), and refCount() operators.
* [RxFunctions ★52](https://github.com/pakoito/RxFunctions) - Advanced Function composition to use with RxJava.
* [rxlint](https://bitbucket.org/littlerobots/rxlint) - An Android lint rule for RxJava code.
* [RxComprehensions ★74](https://github.com/pakoito/RxComprehensions) - Reduce boilerplate in RxJava by abstracting chained flatMaps, concatMaps and switchMaps.

## Testing
* [assertj-rx ★129 ⏳1Y](https://github.com/ribot/assertj-rx) - AssertJ assertions for RxJava Observables.
* [rxpresso ★341](https://github.com/novoda/rxpresso) - Easy Espresso UI testing for Android applications using RxJava.

## Guides

* [RxJava-Android-Samples ★5159](https://github.com/kaushikgopal/RxJava-Android-Samples) - Learning RxJava for Android by example.
* [Intro-To-RxJava ★1150](https://github.com/Froussios/Intro-To-RxJava) - An extensive tutorial on RxJava.

## Articles

* [Rx glitches aren't actually a problem](http://staltz.com/rx-glitches-arent-actually-a-problem.html) - Glitches are temporary inconsistencies emitted by Observables. André Staltz looks at why it's not really a problem.
* [RxJava's repeatWhen and retryWhen, explained](http://blog.danlew.net/2016/01/25/rxjavas-repeatwhen-and-retrywhen-explained/) - `repeatWhen` and `retryWhen` are fairly baffling at first glance. Dan Lew explains the operators in depth.
* [RxJava - The Problem with Subjects](http://tomstechnicalblog.blogspot.co.uk/2016/03/rxjava-problem-with-subjects.html) - Thomas Nield explains why `Subject` is not a panacea.
* [Using RxJava Observable's Completion Semantics for Greater Good](https://adelnizamutdinov.github.io/blog/2015/01/23/using-rxjavas-observable-semantics-for-greater-good/) - Adel Nizamutdinov talks about `Observable`’s completion semantics and `Subscriber.add(Subscription)` method.

## Tools

* [RxMarbles](http://rxmarbles.com/) - Interactive diagrams of Rx Observables.

## Community

* [Google Group](http://groups.google.com/d/forum/rxjava)
* [StackOverflow](http://stackoverflow.com/search?q=rx-java)
* [`@RxJava` on Twitter](http://twitter.com/RxJava)
* [`ReactiveX/RxJava` on Gitter](https://gitter.im/ReactiveX/RxJava)
* [GitHub Issues](https://github.com/ReactiveX/RxJava/issues)

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Jokubas Dargis](http://jokubasdargis.net/) has waived all copyright and related or neighboring rights to this work.
---
<p align="center">
	This list is a copy of <a href="http://github.com/eleventigers/awesome-rxjava">eleventigers/awesome-rxjava</a> with ranks
</p>

<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-100705027-1', 'auto');
  ga('send', 'pageview');

</script>