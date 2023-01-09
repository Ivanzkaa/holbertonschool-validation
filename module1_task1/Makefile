build :
	hugo

clean:
	rm -rf /.dist

post:
	hugo new post/$(POST_NAME).md
	sed -i '2s/title: .*/title: "$(POST_TITLE)"/' content/posts/$(POST_NAME).md
