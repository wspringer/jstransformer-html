# README 

![Circle Build](https://circleci.com/gh/wspringer/jstransformer-html.png?circle-token=:circle-token)

Turns unformatted (and perhaps compressed HTML) into something readable. Basically just a jstransformer wrapper around [html](https://www.npmjs.com/package/html).

If you happen to be in pug:

```pug
p Some HTML snippet
pre:html <li>foo</li><li>bar</li>
```

Resulting in:

```html
<p>Some HTML snippet</p>
<pre>&lt;li&gt;foo&lt;/li&gt;
&lt;li&gt;bar&lt;/li&gt;</pre>
```