# Deep Rock Galactic Control Flow Graphs

[Class hierarchy](https://trumank.github.io/drg-control-flow-graphs)

Generated using [kismet-analyzer](https://github.com/trumank/kismet-analyzer):

    ./kismet-analyzer run-tree unpacked-drg/FSD drg-control-flow-graphs/out
    ./kismet-analyzer hierarchy unpacked-drg/FSD/Content drg-control-flow-graphs/hierarchy.dot
    find drg-control-flow-graphs/ -type f -name "*.dot" -print0 | parallel -v -0 dot "{}" -Tsvg -o "{//}/{/.}.svg"
