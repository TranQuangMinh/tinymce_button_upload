# tinymce_button_upload

## Cấu trúc json responce của link upload 
```javascript
{
    "status": 200,
    "message": "Create file successfully.",
    "file_name": "58b10751d88f7_1487996753.jpg",
    "relative_path": "2017\/02\/58b10751d88f7_1487996753.jpg",
    "result": {
        "full": {
            "url": "http://domain\/asset\/uploads\/images\/2017\/02\/58b10751d88f7_1487996753.jpg",
            "width": 729,
            "height": 597,
            "path": "2017\/02\/58b10751d88f7_1487996753.jpg"
        },
        "thumbnail": {
            "url": "http://domain\/asset\/uploads\/images\/thumbnail\/2017\/02\/58b10751d88f7_1487996753.jpg",
            "width": 500,
            "height": 427,
            "path": "thumbnail\/2017\/02\/58b10751d88f7_1487996753.jpg"
        },
        "thumbnail_small": {
            "url": "http://domain\/asset\/uploads\/images\/thumbnail_200\/2017\/02\/58b10751d88f7_1487996753.jpg",
            "width": 200,
            "height": 171,
            "path": "thumbnail_200\/2017\/02\/58b10751d88f7_1487996753.jpg"
        }
    }
}
```

## Cấu hình

```javascript
 tinymce.init({
 	/* .. */
	image_url_upload: configApp.url.load_upload_image_article_ajax,
 	plugins: [
                '..',
                '.. image ..',
		'..'
            ],
    	toolbar1: [ .. image .. ]
	/* .. */
})	
```
