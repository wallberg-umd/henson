# henson
Experimental: Static website version of the Jim Henson Works at the
University of Maryland, https://digital.lib.umd.edu/henson

## Building

```
docker build -t henson .
docker run -it --rm -p 8080:80 henson
open 'http://localhost:8080'
```

## License

See the [LICENSE](LICENSE.txt) file for license rights and limitations.