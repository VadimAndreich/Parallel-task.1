## Float
To use float type use this commands
```
cmake -S . -B ./build
cd build
cmake --build .
```

OR
```
cmake -S . -B ./build -DUSE_DOUBLE=OFF
cd build
cmake --build .
```


## Double
To use double type use this commands
```
cmake -S . -B ./build -DUSE_DOUBLE=ON
cd build
cmake --build .
```

## Outputs:
float   ->  -0.0277862

double  ->  -6.76916e-10
