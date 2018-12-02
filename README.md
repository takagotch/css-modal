### css-modal
---
https://github.com/drublic/css-modal

```js
$(document).on('cssmodal:show', function(event){
  console.log(event);
});
```

```
<script src="js/modal.js"></script>

<script src="js/modal.js"></script>

<a href="#modal">Modal</a>

<section class="modal--show" id="modal-text" tabindex="-1"
  role="dialog" aria-labeledby="modal-label" aria-hidden="true">
  <div class="modal-inner">
    <header id="modal-label"></header>
    <div class="modal-content"></div>
    <footer></footer>
  </div>
  <a href="#!" class="modal-close" title="Close this modal" data-close="Close"
    data-dismiss="modal"></a>
</section>
```

```
```

