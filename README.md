To modify the Jupyter notebook, use [IHaskell][0]. Mount the root directory of
this repo into the container.

```
docker run -it -p8888:8888 -v $PWD:/home/jovyan/advent-2018 ihaskell:latest
```

[0]: https://github.com/gibiansky/IHaskell
