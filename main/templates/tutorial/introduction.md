Before you begin you should go through the
[requirements]({{url_for('requirement')}}) and make sure that you have:

# for section in config.REQUIREMENT
{% if loop.last %} and {% elif not loop.first %},{% endif %} [{{section[1]}}]({{url_for('requirement')}}{{'#'}}{{section[0]}})
#- endfor
.

We are also going to assume that you will follow all the suggested names
for the directories and files, because in some steps we might refer to
what was suggested without further explanations. If you decide to have
your own names, continue at your own risk.

In this
tutorial we're not going to explain how Google App Engine works, so if you
have never played with it before you should at least finish the
[Getting Started: Python 2.7](https://developers.google.com/appengine/docs/python/gettingstartedpython27/)
before continuing with this one.
