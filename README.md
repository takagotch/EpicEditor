### EpicEditor
---
https://github.com/OscarGodson/EpicEditor

```js
var editor = new EpicEditor().load();

var editor = new EpicEditor({basePath: '/static/lib/epiceditor'}).load();

var opts = {
  container: 'epiceditor',
  textarea: null,
  file: {
    name: 'epiceditor',
    defaultContent: '',
    autoSave: 100
  }
}
var editor = new EpicEditor(opts);

editor.load(funciton(){
  console.log("Editor loaded.")
});
```

```
scp -r EpicEditor/epiceditor you@webserver:public_html/static/lib/
```

```
```


