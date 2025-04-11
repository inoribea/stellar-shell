# astro-scripts

The scripts in this project are function calls for the fish shell and rely on the fish shell. They have not been tested on other terminals.

The scripts rely on astroquery. Please install it yourself to ensure normal calls.

Because the support for the JPL Horizons database is added, at least the dependencies of tabulate and pandas are required in addition to the ontology.

## astroquery

``` fish
astroquery

Available astroquery commands:
  astroquery list       # List all available astroquery services
  astroquery simbad     # Query SIMBAD database
  astroquery vizier     # Query VizieR catalogs
  astroquery gaia       # Query Gaia database
  astroquery skyview    # Get images from SkyView
  astroquery ned        # Query NED database
  astroquery jplhorizons # Query JPL Horizons for solar system objects"
```

## fits-viewer

```fish
fits-view

  --cmap=COLORMAP   Set colormap (default: viridis)
  --log             Use logarithmic scaling
  --save=FILENAME   Save plot to file instead of displaying
```

thanks for claude-sonnet

