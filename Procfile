# This file triggers honcho (the Python version of foreman) to launch the processes defined in Procfile.dynoplex on a single Heroku dyno (allowing it to run for free by default).  If you wish to run a scaleable sentry server on heroku, you should replace this file with the contents of Procfile.dynoplex to allocate more than a single dyno to your application.
web: honcho start -f Procfile.dynoplex
