# Udagram Image Filtering Microservice

This is a simple cloud application developed alongside the Udacity Cloud Engineering Nanodegree. It allows users to register and log into a web client, post photos to the feed, and process photos using an image filtering microservice.

### How to run this project?

After cloning the project, open a terminal and run:
```
npm i
```
After the dependencies are installed, run:
```
npm run start
```

The API to apply a filter to the image, will be available at the URL: http://localhost:8082/filteredimage

To test you must pass an image URL, for example:

```
http://localhost:8082/filteredimage?image_url=https://purepng.com/public/uploads/large/91508357216yeelfspjzpul1x84hidz5nt25xxyfydypneim6sgtd2i8fu1chxs9kj410yjlwx0fnwg6dw212ubhyjyaqhkyejwdwxkb1rvgmzt.png
```

Image before filter

![input.PNG](deployment_screenshot%2Finput.PNG)

Image after filter

![filteredimage_result.jpeg](deployment_screenshot%2Ffilteredimage_result.jpeg)

### AWS Elastic Beanstalk

Elastic Beanstalk App URL:

http://huanvc-full-stack-apps-dev.us-east-1.elasticbeanstalk.com

http://huanvc-full-stack-apps-dev.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://purepng.com/public/uploads/large/91508357216yeelfspjzpul1x84hidz5nt25xxyfydypneim6sgtd2i8fu1chxs9kj410yjlwx0fnwg6dw212ubhyjyaqhkyejwdwxkb1rvgmzt.png
