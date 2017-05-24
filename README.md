The theme is here: https://github.com/justin-calleja/hipaper-based

Install it by cloning that repo into `themes/hipaper`:

`git clone https://github.com/justin-calleja/hipaper-based themes/hipaper`

In existing posts you should see items like so:

```html
<div class="quizpo-section">
  <div class="quizpo-item" style="display: none">
  Form (as opposed to substance)
  </div>
  <button class="quizpo-show-hide-btn">Show / Hide</button>
</div>
```

in your posts you should copy this structure. The theme will be able to hook into these added HTML elements and provide "show / hide" functions.

### Add new posts

Copy the existing posts in `source/_posts` to create new content.

### Run locally

Run with `hexo server` to run locally.
