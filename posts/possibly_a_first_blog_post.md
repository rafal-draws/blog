# The idea

The idea is to create a minimal blog framework, that parses the markdown files and uses github as a database.

Not only the posts have the creation date parsed from the repository, but also changes are trackable.

This is an example. This wasn't here, but you can definitely see it!

The posts are going to be versioned, with commit hash.

## How about the code?


```rust

// the idea is to enable it, possibly via some js library downloaded client side.

let nobody = tell(you)
            .what_you_can()
            .or_cant_do()
            .unwrap();

```


## Attachment support

The attachments must be placed under ```/resources``` folder in the repository containing posts in .md format.



![cat](/resources/cat.gif)

equals to 
```
![cat](/resources/cat.gif)
```

Of course, you can modify it as per your liking.


> this

>> is

*a*

**test**