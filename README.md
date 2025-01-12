This repository contains a Swift function that calculates the average of an array of Double values. However, the original implementation has a potential integer overflow issue if the array contains a very large number of elements whose sum might exceed the maximum representable value for Double. The solution demonstrates how to mitigate this risk using a more robust approach.