---
layout: documentation
title: Developers instructions (Gradle / Maven)
menu: Developers (Gradle / Maven)
permalink: /documentation/developers/
---


### Build TermSuite from source with Git and Gradle

~~~
$ git clone git@github.com:termsuite/termsuite-core.git
$ cd termsuite-core
$ gradle
~~~

The jar will then be found under ./build/libs.

### Use TermSuite as a Maven dependency

{% highlight xml %}

<dependency>
  <groupId>fr.univ-nantes.termsuite</groupId>
  <artifactId>termsuite-core</artifactId>
  <version>{{termsuite.version}}</version>
</dependency>

{% endhighlight %}