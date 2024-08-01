## How to use Boring Avatars service

To generate a custom avatar just embed the following URL `https://avatars.cyanfox.de/` and append a variant, size and a username to generate a custom avatar.

### Variants
You can use one of the variants `marble`, `beam`, `pixel`, `sunset`, `ring` or `bauhaus`. 

```
https://avatars.cyanfox.de/beam
```

![Avatar using marble variant](https://avatars.cyanfox.de/beam)

### Custom size

```
https://avatars.cyanfox.de/marble/40

```

![Avatar of 120px](https://avatars.cyanfox.de/marble/40)


```
https://avatars.cyanfox.de/marble/160

```

![Avatar of 120px](https://avatars.cyanfox.de/marble/120)


### Custom colors
You can pass an array of colors using the parameter `color` 

```
https://avatars.cyanfox.de/marble/120/Maria%20Mitchell?colors=264653,2a9d8f,e9c46a,f4a261,e76f51
```
![Avatar for Maria Mitchell](https://avatars.cyanfox.de/marble/120/Maria%20Mitchell?colors=264653,2a9d8f,e9c46a,f4a261,e76f51)


### Name

You can use a `username`, `email` or any random text to generate a unique `avatar`. 


```
https://avatars.cyanfox.de/marble/120/Maria%20Mitchell
```
![Avatar for Maria Mitchell](https://avatars.cyanfox.de/marble/120/Maria%20Mitchell)


### Random avatar
If you just want to use random avatars without providing usernames, you can use the root endpoint. You will receive an `svg` image with a 80*80px size using the `marble` variant.

```
https://avatars.cyanfox.de/
```

![Random avatar](https://avatars.cyanfox.de/)

