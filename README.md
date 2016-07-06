# spheremap-demos

Exploratory work with sphere maps as seen on the Mapzen blog, read [here](https://mapzen.com/blog/sphere-maps/). Please read Peter Richardson's blog post [Mapping Mountains](https://mapzen.com/blog/mapping-mountains/) post on the [Mapzen blog](http://mapzen.com/blog) for more info on sphere maps.

<img src="https://tangrams.github.io/spheremap-demos/img/crayon-map.jpg">

## Sphere Map examples
- pencil: https://tangrams.github.io/spheremap-demos/?url=styles/pencil2.yaml#12/37.8090/-122.2220
- smudged pencil: https://tangrams.github.io/spheremap-demos/?url=styles/pencil.yaml#12/37.8090/-122.2220
- colored pencil: https://tangrams.github.io/spheremap-demos/?url=styles/color-pencil.yaml#12/37.8090/-122.2220
- markers: https://tangrams.github.io/spheremap-demos/?url=styles/marker.yaml#12/37.8090/-122.2220
- crayon: https://tangrams.github.io/spheremap-demos/?url=styles/crayon.yaml#12/37.8090/-122.2220
- watercolors: https://tangrams.github.io/spheremap-demos/?url=styles/watercolor2.yaml#12/37.8090/-122.2220
- watercolors: https://tangrams.github.io/spheremap-demos/?url=styles/watercolor.yaml#12/37.8090/-122.2220
- stripes: https://tangrams.github.io/spheremap-demos/?url=styles/stripes.yaml#12/37.8090/-122.2220
- glitch: https://tangrams.github.io/spheremap-demos/?noscroll&url=styles/glitch.yaml#12/37.8773/-121.9292
- Roland Flexner: https://tangrams.github.io/spheremap-demos/?noscroll&url=styles/flexner.yaml#12/37.8773/-121.9292
- Kelsey Brookes: https://tangrams.github.io/spheremap-demos/?noscroll&url=styles/kelseybrookes.yaml#12/37.8773/-121.9292
- Walkabout sphere map: https://tangrams.github.io/spheremap-demos/?noscroll&url=styles/walkabout.yaml#12/37.8773/-121.9292


### To run locally:

Start a web server in the repo's directory:

    python -m SimpleHTTPServer 8000
    
If that doesn't work, try:

    python -m http.server 8000
    
Then navigate to, eg: [http://localhost:8000/?url=styles/pencil.yaml](http://localhost:8000/?url=styles/pencil.yaml)
