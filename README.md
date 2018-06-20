# hexo-readingtime
_Not maintained by Nodes anymore_

A plugin that provides a reading time estimate to your hexo posts (e.g. '8 min read'). It's a wrapper around the [reading-time module](https://github.com/ngryman/reading-time).

## Installation

`npm install --save hexo-readingtime`

## Usage

In your posts, you can access the reading time results via the 'readingTime' property on the `post` or `page` object. For example (in Swig):

```
{{ post.readingTime.text }}
```

Where `text` is one of several properties on the `readingTime` object. The `readingTime` object looks like this:
 `{"text":"8 min read","minutes":7.92,"time":475200,"words":1584}` and comes from the [reading-time module](https://github.com/ngryman/reading-time).
