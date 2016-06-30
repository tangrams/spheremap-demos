# spheremap-demos

Exploratory work with sphere maps. Please read Peter Richardson's blog post [Mapping Mountains](https://mapzen.com/blog/mapping-mountains/) post on the [Mapzen blog](http://mapzen.com/blog) for more info on sphere maps.

<img src="https://tangrams.github.io/spheremap-demos/img/crayon-map.jpg">

## Sphere Map examples
- pencil: https://tangrams.github.io/spheremap-demos/?url=styles/pencil2.yaml#12/37.8090/-122.2220
- smudged pencil: https://tangrams.github.io/spheremap-demos/?url=styles/pencil.yaml#12/37.8090/-122.2220


### To run locally:

Start a web server in the repo's directory:

    python -m SimpleHTTPServer 8000
    
If that doesn't work, try:

    python -m http.server 8000
    
Then navigate to, eg: [http://localhost:8000/?url=styles/contours.yaml](http://localhost:8000/?url=styles/contours.yaml)
