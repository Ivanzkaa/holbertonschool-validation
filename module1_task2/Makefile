build: ##building a website from scratch
	hugo

clean: ##cleanup the content of the directory
	rm -rf ./dist/

post: ##creating a new blog post
	hugo new posts/$(POST_NAME).md
	sed -i '2s/title: .*/title: "$(POST_TITLE)"/' content/posts/$(POST_NAME).md

help: ##help in the commands
	cat Makefile | grep '##' | tr -d '##'
