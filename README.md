# 601_Mini_project_3:
EC 601 Mini Project- A python project that downloads images from your twitter feed, converts them to a video and 
uses Google's Video Intelligence API to describe the content of the video.

## Built using

* Mysql
* MongoDB 
* Python 2.7.10 
* Tweepy 3.6.0
* FFMPEG version 4.0.2
* google-cloud-videointelligence 1.3.0

## Paths

* Path to images ./twitter_images
* Path to video ./twitter_images/vid.mp4

## User Guide

* Run using: python main.py
* images from twitter are stored in the format: img_%03d.jpg</br>
* ```google_vision.py``` and ```google_vision_mongo.py``` will upload data to mysql and mongodb respectively.
* ```check_database_sql.py``` and ```check_database_mongo.py``` are apis used to query data and get information from database.

## Example Output

*601_Mini_project_APIs/src/Screen Shot 2018-09-18 at 11.02.56 PM.png

## References

* Google Cloud Video Intelligence API python Frame level and video level example referred from https://cloud.google.com/video-intelligence/docs/label-tutorial
* README Template referred from https://gist.githubusercontent.com/PurpleBooth/109311bb0361f32d87a2/raw/8254b53ab8dcb18afc64287aaddd9e5b6059f880/README-Template.md 

