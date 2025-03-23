# CI-Test

# 机上でのbuild, 実行方法

## install tool
```
# Ubuntu/Debian
sudo apt update
sudo apt install -y cmake g++ make
```

## build
```
mv /path/to/cpp-ci-test
mkdir build
cd build
cmake ..
make
```
## execute
```
mv /path/to/cpp-ci-test
./build/main
```