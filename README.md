# MCReminder
Discord bot written in python and [disco](https://github.com/b1naryth1ef/disco/). MC Listens to messages until certain patterns are met, triggering an answer. The patterns and the type of answer to craft are completely configurable using a single JSON file. Supports embeds and attachments, too.  
Developed for the Discord channel of [gameloop.it](https://gameloop.it/), the Italian gamedev community.

# Installation
Have python3+ installed. Install disco:
```bash
python -m pip install disco-py
```
disco can be installed with some additional dependencies, check out [their instructions](https://github.com/b1naryth1ef/disco)

If you want to use some advanced features, such as word stems matching, you will also need nltk and polyglot:
```bash
python -m pip install nltk
python -m pip install polyglot
```
Be aware that polyglot has some additional dependencies, please refer to its own [installation instructions](http://polyglot.readthedocs.io/en/latest/Installation.html)

# Deployment
See doc/HOWTODEPLOY.
