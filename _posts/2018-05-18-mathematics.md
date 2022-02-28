---
title: "Arms Race"
layout: post
date: 2018-05-18
image: /assets/images/markdown.jpg
headerImage: false
# tag:
# - markdown
# - elements
star: false
category: blog
description: Differential Equs. in Arms Race Model
---
<img class="image" src="{{ site.url }}/assets/images/cover.png" alt="Alt Text">
---

## Introduction

An arms race, in its original usage, is a competition between two or more states to have the best
armed forces. Each party competes to produce more weapons, larger military, superior military
technology, etc. in a technological escalation.
Back in the days of the cold war between the United States of America and the Soviet Union, the
greatest interest was in the **ARM RACE** between the two countries. And since the end of the
war, most of the scientists had focused on the regional antagonisms to analyze it.
And before we get more further in the explanation of our subject we must mention who the
pioneer in this field was and what did he contribute with.
**Lewis fry Richardson**.

---

## About L.Richardson

<div class="side-by-side">
    <div class="toleft" style="  position: relative; left: 100px;" >
        <img class="image" src="{{ site.url }}/assets/images/richard.png" alt="Alt Text">
    </div>

    <div class="toright">
        <p>Richardson, born in 1881 and died in 1953, was an English mathematician and the pioneer in mathematical techniques and its relation in wars and its causes, and weather forecasting. Richardson's Quaker beliefs entailed an ardent pacifism that exempted him from military service during World War I as a conscientious objector, though this subsequently disqualified him from having any academic post. Richardson worked from 1916 to 1919 for the Friends' Ambulance Unit attached to the 16th French Infantry Division. After the war, he rejoined the Meteorological Office but was compelled to resign on grounds of conscience when it was amalgamated into the Air Ministry in 1920. He subsequently pursued a career on the fringes of the academic world before retiring in 1940 to research his own ideas.</p>
    </div>
</div>

# Headings can be small

## Headings can be small

### Headings can be small

#### Headings can be small

{% highlight raw %}

# Heading

## Heading

### Heading

#### Heading

{% endhighlight %}

---

## Lists

### Ordered list

1. Item 1
2. A second item
3. Number 3

{% highlight raw %}

1. Item 1
2. A second item
3. Number 3
{% endhighlight %}

### Unordered list

* An item
* Another item
* Yet another item
* And there's more...

{% highlight raw %}

* An item
* Another item
* Yet another item
* And there's more...
{% endhighlight %}

---

## Paragraph modifiers

### Quote

> Here is a quote. What this is should be self explanatory. Quotes are automatically indented when they are used.

{% highlight raw %}
> Here is a quote. What this is should be self explanatory.
{% endhighlight raw %}

---

## URLs

URLs can be made in a handful of ways:

* A named link to [Mark It Down][3].
* Another named link to [Mark It Down](https://google.com/)
* Sometimes you just want a URL like <https://google.com/>.

{% highlight raw %}

* A named link to [MarkItDown][3].
* Another named link to [MarkItDown](https://google.com/)
* Sometimes you just want a URL like <https://google.com/>.
{% endhighlight %}

---

## Horizontal rule

A horizontal rule is a line that goes across the middle of the page.
It's sometimes handy for breaking things up.

{% highlight raw %}
---

{% endhighlight %}

---

## Images

Markdown can also contain images. I'll need to add something here sometime.

{% highlight raw %}
![Markdowm Image][/image/url]
{% endhighlight %}

![Markdowm Image][5]

*Figure Caption*?

{% highlight raw %}
![Markdowm Image][/image/url]
<figcaption class="caption">Photo by John Doe</figcaption>
{% endhighlight %}

![Markdowm Image][5]
<figcaption class="caption">Photo by John Doe</figcaption>

*Bigger Images*?

{% highlight raw %}
![Markdowm Image][/image/url]{: class="bigger-image" }
{% endhighlight %}

![Markdowm Image][5]{: class="bigger-image" }

---

## Code

A HTML Example:

{% highlight html %}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Document</title>
</head>
<body>
    <h1>Just a test</h1>
</body>
</html>
{% endhighlight %}

A CSS Example:

{% highlight css %}
pre {
    padding: 10px;
    font-size: .8em;
    white-space: pre;
}

pre, table {
    width: 100%;
}

code, pre, tt {
    font-family: Monaco, Consolas, Inconsolata, monospace, sans-serif;
    background: rgba(0,0,0,.05);
}
{% endhighlight %}

A JS Example:

{% highlight js %}
// Sticky Header
$(window).scroll(function() {

    if ($(window).scrollTop() > 900 && !$("body").hasClass('show-menu')) {
        $('#hamburguer__open').fadeOut('fast');
    } else if (!$("body").hasClass('show-menu')) {
        $('#hamburguer__open').fadeIn('fast');
    }

});
{% endhighlight %}

[1]: https://daringfireball.net/projects/markdown/
[2]: https://www.fileformat.info/info/unicode/char/2163/index.htm
[3]: https://daringfireball.net/projects/markdown/basics
[4]: https://daringfireball.net/projects/markdown/syntax
[5]: https://kune.fr/wp-content/uploads/2013/10/ghost-blog.jpg
