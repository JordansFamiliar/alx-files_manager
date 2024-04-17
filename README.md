# Files Manager

The goal of this project is to build an application that can upload and view files with the following functionality:

- User authentication
- Thumbnail generation
- Uploading new files
- Managing user permissions
- Viewing files
- Listing files

## Testing and Jobs

A queueing job mechanism is included in the project which creates thumbnails when photos have been uploaded to the app.
When a new user is created, it also leverages this feature to generate a welcome message. Bull is used in all of this. 

Chai and Mocha has been used for testing the app.

## Authors
Jordan Williams: jordanlw1997@gmail.com <br>
Keitumetse Molefe: kr.molefe98@gmail.com