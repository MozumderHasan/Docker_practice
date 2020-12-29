# Docker_practice using custom image
Docker importent command and learning roadmap
#docker Install Command
>>>curl -fsSL https://get.docker.com -o get-docker.sh (Download docker)

>>>sudo sh get-docker.sh (Install Docker)

>>>docker commit af90cebc9611 hasanweight/custom_django_web
	(custome image create kore)

>>>docker run -it -d hasanweight/custom_django_web bash(custom image er container toiri kore)
	docker exec -it 50d3a2a558aa bash (container er bhitor shell create kore)

>>>docker push hasanweight/custom_django_web(docker hub a store hobe image)

>>>docker run -it -d hasanweight/custom_django_web(docker hub theke image download kore anbe)

----------------******using git for docker*******----------------------------
>>> git clone git_path
>>> pip install -t requirement.txt(specific path)
>>> docker-compose build 
>>> python manage.py runserver (for django project)
