# docker-ionic


## Usage

```
alias ionic="docker run --rm  --privileged -v $(pwd):/root/app:rw --net host ayyazzafar/ionic ionic" 
```
now you can access ionic from your bash


```
ionic serve
```

To serve in moible or emulator:

```
	ionic cordova run android -lc --address localhost
```
