## submarine-cable-map-downloader



```
submarine-cable-map-downloader [path] [flags]
```

### Options

```
  -c, --compression string   PNG compression level (one of default, none, fast, best) (default "default")
  -f, --format string        Tile format. Try png, png8, png24. (default detected)
  -h, --help                 help for submarine-cable-map-downloader
  -n, --no-crop              Download the entire square map instead of cropping
  -p, --parallelism int      Number of goroutines to use (default 16)
      --tile-max-x int       X tile max (default determined by year and zoom)
      --tile-max-y int       Y tile max (default determined by year and zoom)
      --tile-min-x int       X tile min (default determined by year and zoom)
      --tile-min-y int       Y tile min (default determined by year and zoom)
  -y, --year int             Year to download (default latest available)
  -z, --zoom int             Zoom level (default 6)
```

