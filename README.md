# Generate chart png image via highcharts and phantomjs

Links:

https://github.com/highslide-software/highcharts.com/tree/master/exporting-server/phantomjs

http://www.highcharts.com/component/content/article/2-news/52-serverside-generated-charts

http://export.highcharts.com/demo

## Launch generation service

```
chmod +x example_post_request.sh start_server.sh

./start_server.sh
```

## Update the request body file

```
vim example_body.json
```

## Generate image

```
./example_post_request.sh
```

The image will be stored to ```images/img.png```
