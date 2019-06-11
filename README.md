# Video Input Preview ([Demo](https://jsfiddle.net/Zenoo0/zhpbtko9/))

Display a preview for your video inputs easily

### Doc

* **Installation**

Simply import video-input-preview into your HTML.
```
<link rel="stylesheet" type="text/css" href="https://unpkg.com/video-input-preview@0.0.2/VideoInputPreview.min.css">
<script src="https://unpkg.com/video-input-preview@0.0.2/VideoInputPreview.min.js"></script>
```
* **Documentation**

See the offical [documentation](https://zenoo.github.io/video-input-preview/VideoInputPreview.html) for more in-depth informations.

* **How to use**

You can either use data attributes or the `VideoInputAttribute` class to initialyze your inputs:
```
<input type="file" accept="video/*" data-video-preview="https://link.to.your.preview.mp4">
// OR
let preview = new VideoInputPreview(input, {
  preview: 'https://link.to.your/preview.mp4',        // Optional | Preview displayed
  uploadIcon: 'https://link.to.your.upload/icon.png', // Optional | Icon used when no preview is displayed
  lang: 'en',                                         // Optional | Language used
  dictionary: null                                    // Optional | Allow for custom language
});
```

* **Methods**

See the [documentation](https://zenoo.github.io/video-input-preview/VideoInputPreview.html) for the method definitions.


* **Example**

See this [JSFiddle](https://jsfiddle.net/Zenoo0/zhpbtko9/) for a working example

## Authors

* **Zenoo** - *Initial work* - [Zenoo.fr](http://zenoo.fr)
