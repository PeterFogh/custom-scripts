# Snow Cover Change Detection

## Evaluate and visualize
 - [Sentinel Playground temporal](https://apps.sentinel-hub.com/sentinel-playground-temporal/?source=S2&lat=52.142338229345874&lng=-117.39921569824219&zoom=10&preset=CUSTOM&layers=B04,B03,B02&maxcc=30&gain=1.0&temporal=true&gamma=1.0&time=2015-01-01%7C2018-08-31&atmFilter=&showDates=false&evalscript=LyoKQXV0aG9yOiBLYXJsIENoYXN0a28KKi8KCgpmdW5jdGlvbiAgICBzZXR1cCAoZHNzKSB7CiAgc2V0SW5wdXRDb21wb25lbnRzKFtkc3MuQjAzLGRzcy5CMTFdKTsKICBzZXRPdXRwdXRDb21wb25lbnRDb3VudCgzKTsKfQoKZnVuY3Rpb24gY2FsY05EU0koc2FtcGxlKSB7CiAgbmRzaSA9IChzYW1wbGUuQjAzIC0gc2FtcGxlLkIxMSkvICgwLjAxICsgc2FtcGxlLkIwMyArIHNhbXBsZS5CMTEpOwogIHJldHVybiAoKG5kc2k%2BMC4yKSYoc2FtcGxlLkIwMz4wLjE1KSkgPyAobmRzaSkgOiAwLjAKfQoKZnVuY3Rpb24gZXZhbHVhdGVQaXhlbChzYW1wbGVzLHNjZW5lcykgewogIHZhciBhdmcxID0gMDsKICB2YXIgY291bnQxID0gMDsKICB2YXIgYXZnMiA9IDA7CiAgdmFyIGNvdW50MiA9IDA7CiAgdmFyIGF2ZzMgPSAwOwogIHZhciBjb3VudDMgPSAwOwogIHZhciBlbmRNb250aCA9IHNjZW5lc1swXS5kYXRlLmdldE1vbnRoKCk7CgogIGZvciAodmFyIGk9MDtpPHNhbXBsZXMubGVuZ3RoO2krKykgewogICAgICB2YXIgbmR2aSA9IGNhbGNORFNJKHNhbXBsZXNbaV0pOwogICAgICBpZiAoc2NlbmVzW2ldLmRhdGUuZ2V0TW9udGgoKT09ZW5kTW9udGgpCiAgICAgIHsKCQlhdmczID0gYXZnMyArIG5kdmk7CiAgICAgICAgY291bnQzKys7CiAgICAgIH0KICAgICAgZWxzZSBpZiAoc2NlbmVzW2ldLmRhdGUuZ2V0TW9udGgoKT09KGVuZE1vbnRoLTEpKQogICAgICB7CgkJYXZnMiA9IGF2ZzIgKyBuZHZpOwogICAgICAgIGNvdW50MisrOwogICAgICB9CiAgICAgIGVsc2UKICAgICAgewoJCWF2ZzE9IGF2ZzEgKyBuZHZpOwogICAgICAgIGNvdW50MSsrOwogICAgICB9CgogIH0KICBhdmcxID0gYXZnMS9jb3VudDE7CiAgYXZnMiA9IGF2ZzIvY291bnQyOwogIGF2ZzMgPSBhdmczL2NvdW50MzsKCiAgcmV0dXJuIFthdmcxKjUsYXZnMio1LGF2ZzMqNV07Cgp9CmZ1bmN0aW9uIGZpbHRlclNjZW5lcyAoc2NlbmVzLCBpbnB1dE1ldGFkYXRhKSB7CiAgICByZXR1cm4gc2NlbmVzLmZpbHRlcihmdW5jdGlvbiAoc2NlbmUpIHsKCSAgcmV0dXJuIHNjZW5lLmRhdGUuZ2V0VGltZSgpPj0oaW5wdXRNZXRhZGF0YS50by5nZXRUaW1lKCktMyozMSoyNCozNjAwKjEwMDApIDsKICAgIH0pOwp9Cg%3D%3D){:target="_blank"}


## General description of the script

The Snow Cover Change Detection script calculates the NDSI for any given region for the last three months and renders the results so that areas which have gained/lost snow can be easily identified.

This script works great for viewing snowfall in the autumn months or snow retreat in the spring. Additionally, this script can be used to visualize glacial retreat or advance in polar or high mountain regions.

## Author of the script

Karl Chastko

## Description of representative images

The images below demonstrate how the script can be used to track glacial retreat and spring snowmelt.

The first image shows the summer retreat of the Athabasca glacier in Western Alberta Canada from June 2018 - August 2018.
![Snow Cover Change Detection script example 1](fig/NDSI_results_athabasca.png)

The second image displays patterns of spring thaw (largely related to local topography) along the Manitoba escarpment in Manitoba Canada.
![Snow Cover Change Detection script example 2](fig/NDSI_results_manitoba.png)

Generally speaking regions in blue and green highlight areas which have high snow cover in the earliest months while red values highlight areas which maintain snow cover in the later months. Combinations of these colors represent areas which remain snow covered across multiple time periods. Images show the result of the script using the default parameters.
