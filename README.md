# PhotoSwipe_custom_script
> 一 A JavaScript Integrated [PhotoSwipe](https://github.com/dimsemenov/PhotoSwipe) Image Preview Plugin
## Requirements
[PhotoSwipe](https://github.com/dimsemenov/PhotoSwipe)
## Demo
[Live Demo >>](https://ls1231.github.com/vue-preview/)
## Usage
Base
```html
<a href="https://source.unsplash.com/300x300/?sig=0" data-size="300x300">
  <img src="https://source.unsplash.com/300x300/?sig=0" alt="Image caption" />
</a>
```
Groups (data-pswp-uid)
```html
<a href="https://source.unsplash.com/300x300/?sig=0" data-size="300x300" data-pswp-uid="g1">
  <img src="https://source.unsplash.com/300x300/?sig=0" alt="Image caption" />
</a>
<a href="https://source.unsplash.com/300x300/?sig=1" data-size="300x300" data-pswp-uid="g2">
  <img src="https://source.unsplash.com/300x300/?sig=1" alt="Image caption" />
</a>
```
Ajax adding
```javascript
newHtml = document.createElement('div');
newHtml.innerHTML = /*data*/;
pSwp(newHtml);
```