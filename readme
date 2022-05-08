#To create this project I used only 6-8 lines of PHP cURL codes and they are used to download an image only and all other things are done using JavaScript like preview thumbnail. I hope you’ve understood the codes.

#Let’s understand how I got a thumbnail from the URL and downloaded it but before this, you’ve to know how YouTube video URL looks like.

#Long URL of the video – https://www.youtube.com/watch?v=ZucPfdPDd2Y
Short URL of the same video – https://youtu.be/ZucPfdPDd2Y
As you can see in both URLs there is the same video ID ZucPfdPDd2Y of 11 lengths long and this ID is unique to each video and we need only this ID to get the thumbnail of this video. Using JavaScript, first, I got the user entered video URL and split it from the v= if the URL is long or split it from /be if the URL is short to get only video ID.

#After I got the video ID, https://img.youtube.com/vi/VID_ID/maxresdefault.jpg is the thumbnail URL of the YouTube video. If you open this URL by replacing VID_ID with some random video ID then you’ll get a thumbnail of that video. I just replaced this VID_ID with the user entered video ID and inserted this full URL inside <img src=”thumbnail_url”> to show an image preview and at the same time I passed this URL in value of a hidden input to download this thumbnail using PHP. That’s it after I got a thumbnail, I just download it using PHP cURL.

#Remember, YouTube has four types of thumbnail URLs and in this project, I only used one of them.

##Low-Quality – https://img.youtube.com/vi/VID_ID/sddefault.jpg
##Medium-Quality – https://img.youtube.com/vi/VID_ID/mqdefault.jpg
##Hight-Quality – https://img.youtube.com/vi/VID_ID/hqdefault.jpg
##Max High-Quality – https://img.youtube.com/vi/VID_ID/maxresdefault.jpg
