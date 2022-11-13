For macOS user and assume you have Xcode (otherwise check for xcode-select)

```
brew install cmake git
git clone https://github.com/kylehovey/automata_generator.git
```

```
cd automata_generator
cmake -S .   # take note of the dot "." and it will use the CMakeLists.txt
make          # the above will generate a Makefile
./run-all-trials.sh                  # do some run
```

### Not sure what to do next ???

so to run and generate graph to give the final result we saw in this [beautiful web page](https://kylehovey.github.io/blog/automata-nebula) or discussed in  [hacker news](https://news.ycombinator.com/item?id=33578376)

Is it possible (by looking at the run-all-trials.sh that we can wait for the ./tmp/png to becomes stable and something magic will come out?
