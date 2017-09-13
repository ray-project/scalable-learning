# scalable-learning
Scaling multi-node multi-GPU workloads


## Installing Imagenet

The commands below assume Python is Python 2, so you may need to change the python invoked in the script if your default Python is Python 3

    # Assuming we are starting in repository root
    ROOT="$PWD"
    cd /tmp
    git clone https://github.com/SaMnCo/dl-training-datasets
    cd imagenet/ilsvrc14
    ./00-build.sh "$ROOT/data"

TODO: make own script for this, without the need for the user to specify Python 2.

## Running pytorch example

[https://github.com/pytorch/examples/tree/master/imagenet](Follow steps here).

TODO: copy in relevant files

## Dependencies

TODO: make user-independent aws-magic analogue, pull in docker for pytorch.