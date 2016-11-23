# conferencedb
Website with a list of conferences. This is not an official Google product.

## Getting Started

For install dependence and test your application in local server

1. cd conferencedb
2. npm install -g gulp bower && cd third_party/ && npm install && cd .. && bower install
3. cd third_party/
4. gulp serve


For deploy your application on firebase hosting

1. cd third_party
2. gulp
2. cd ../
3. ONLY FIRST TIME: firebase init 
	1. Chose in Firebase Service: Only hosting
	3. Chose in Public folder: dist
	4. Chose in Rewrite all urls to Index.html: y
	5. Chose in Overwrite index.html: N
	6. Chose your project or create a new project
3. firebase deploy

For test your application before deploy

1. cd third_party
2. gulp serve:dist