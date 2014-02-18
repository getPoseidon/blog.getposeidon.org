blog.getposeidon.org
====================

The official Poseidon weblog 

##Features
* disqus
* google analytics
* responsive theme

##Deploy

to run in production with forever, run the following commands from the root of the project

	npm install
	npm install forever -g
	NODE_ENV=production forever start index.js
