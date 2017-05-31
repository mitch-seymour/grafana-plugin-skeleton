# grafana-plugin-skeleton
A starting point for building your own Grafana plugin. This is a work in progress.

# Ongoing
I am currently compiling some info from the following resources to create this skeleton (work in progress):
* [Grafana code styleguide](http://docs.grafana.org/plugins/developing/code-styleguide/)
* [Clock panel blog post](https://grafana.com/blog/2016/04/08/timing-is-everything.-writing-the-clock-panel-plugin-for-grafana-3.0/)
* More to come soon


# Set up
Before you get started, you will need to install Grafana. If you're using a Mac, the easiest way to install Grafana is via Homebrew.

```bash
# install grafana
$ brew install grafana

# You should see instructions for starting Grafana now. e.g.
$ brew services start grafana

# Or, if you don't want/need a background service you can just run:
$ grafana-server --config=/usr/local/etc/grafana/grafana.ini --homepath /usr/local/share/grafana cfg:default.paths.logs=/usr/local/var/log/grafana cfg:default.paths.data=/usr/local/var/lib/grafana cfg:default.paths.plugins=/usr/local/var/lib/grafana/plugins

```

If you're using Linux or Windows, then follow [these instructions][grafana-build-from-src] for building Grafana from source.

[grafana-build-from-src]: http://docs.grafana.org/project/building_from_source/


