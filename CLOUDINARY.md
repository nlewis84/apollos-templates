# Cloudinary Set Up

This guide will explain how to set up your API with Cloudinary

Add the Heroku add-on to your server

```
heroku addons:create cloudinary
```

Get your newly created bucket URL

```
heroku config:get CLOUDINARY_URL
```

Then add the URL to your local `.env` file to confirm it's working properly

```
CLOUDINARY_URL=<yourCloudinaryUrl>
```
