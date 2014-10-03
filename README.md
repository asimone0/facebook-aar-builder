facebook-aar-builder
=========

A script for assembling an aar file based on any tag in the [facebook-android-sdk] github repository.


##Clone

```sh
git clone https://github.com/tonestuff/facebook-aar-builder
cd <wherever you put it>
```

##Use

```sh
./gradlew -PFB_TAG=<desired tag from facebook repo>
```
**The resulting aar file will be in**  
*./build/outputs/aar*


####Too lazy to look up the tags?


```sh
./gradlew listTags
```


[facebook]:https://github.com/facebook/facebook-android-sdk 

