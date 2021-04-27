# Monte Carlo Sockets

PI computation employing Monte Carlo method with sockets.

## Requirements

Scripts written in linux environment (Ubuntu **18.x** and **20.x**).

- gcc compiler.
```bash
$> sudo apt install gcc 
```
- build-essential package.
```bash
$> sudo apt install build-essential 
```
- make.
```bash
$> sudo apt install make 
```
- cmake.
```bash
$> sudo apt install cmake 
```

## How to build

- Create a build folder.
```bash
$> mkdir build
```
- Run cmake.
```bash
$> cmake build
```
- Run make.
```bash
$> make -C build
```
- Execute the compiled project.
```bash
$> ./build/server
$> ./build/client 
```

## Authors
- David Costa
    - [ds.costa@unesp.br](mailto:ds.costa@unesp.br)
- Murilo Carvalho 
    - [murilo.ignacio@unesp.br](mailto:murilo.ignacio@unesp.br)

## License
This project is licensed under the GNU GENERAL PUBLIC LICENSE - see the [LICENSE](LICENSE) file for more details.