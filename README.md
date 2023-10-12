# Reddit text to speech generator

**_This development for this project has ended, I don't plan on fixing or further supporting this_**

A python gui program to generate reddit text to speech videos from posts or comments.

# Current functionality

- Generate videos for subs based on comments,(askreddit) so reading individual comments.
- Generate videos for subs with longer posts,(entitledparents), so slicing the post into multiple frames to fit the text.
- Easy login, all you need to do, is run `main.py`, you will get a link; go to the link and click allow; Thats it! the credentials are written to a json file so you dont need to repeat this step as long as the `token.json` file is there.
- Ability to cherry pick individual posts for which the video has to be made, within the GUI (refer to screenshots)


# Usage

- do `pip install -r requirements.txt` to install all the dependencies and then, run `python main.py`
- It will prompt you to open a url, open it, then allow "post_scraper" to access your account, then you will be redirected to a browser tab, you can then close it.

# Screenshots

<img src='screenshots/1.2.jpg' width=500px> <img src='screenshots/2.2.jpg' width=500px>

# Backburners

- Converting links and emojis to plain text
