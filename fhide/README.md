# FHide : File Hider #

This rootkit is similar to the
[PHide](https://github.com/nisay759/linux-rootkits/tree/master/phide) rootkit.
It hides files beginning with the prefix « rk_ » that are located on the root of
the filesystem « / »

## Compilation ##
```
	$ make
```

## Installation ## // Made a slight improvement //William Martens
```
	$ sudo insmod fhide.ko prefix="hideme"
```

## Removal ##
```
	$ sudo rmmod fhide
```

## Disclaimer ##

This is an experimental rootkit. Use it at your own risks.
