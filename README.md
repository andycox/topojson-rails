# topojson-rails

**TopoJSON** is an extension of GeoJSON that encodes topology. Rather than representing geometries discretely, geometries in TopoJSON files are stitched together from shared line segments called *arcs*. TopoJSON eliminates redundancy, offering much more compact representations of geometry than with GeoJSON; typical TopoJSON files are 80% smaller than their GeoJSON equivalents. In addition, TopoJSON facilitates applications that use topology, such as [topology-preserving shape simplification](http://bost.ocks.org/mike/simplify/), [automatic map coloring](http://bl.ocks.org/4188334), and [cartograms](http://prag.ma/code/d3-cartogram/).

Want to learn more? [See the wiki.](/mbostock/topojson/wiki)

## Installation

Add the following to your gemfile:

    gem 'topojson-rails'

And then execute:

    $ bundle

Add the following directive to your JavaScript manifest file (application.js):

    //= require topojson

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
