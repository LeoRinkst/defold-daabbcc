This is a fork of the Dynamic Tree(aka AABB Tree) native extension for [Defold Engine](https://www.defold.com/).

It was modified to use AABB bounds directly, instead of using center position and size.

DAABBCC build by using Box2D’s [Dynamic Tree](https://box2d.org/documentation/md_collision.html#autotoc_md46).  

**Credits**  
[Box2D](https://github.com/erincatto/box2d) by  [Erin Catto](https://x.com/erin_catto)  
[Original DAABBCC](https://github.com/selimanac/defold-daabbcc)  by [Selim Anaç](https://github.com/selimanac/)

**What is DAABBCC?**

A Dynamic AABB Tree is a binary search algorithm for fast overlap testing. Dynamic AABB trees are well-suited for general-purpose use and can handle moving objects efficiently. This data structure provides an effective method for detecting potential overlap between objects.  

DAABBCC is not a physics engine. It does not include narrow-phase collision detection or ~manifold generation~<sup>1</sup>.  

It is particularly well-suited for casual games, platformers, bullet-hell, top-down games, server-side headless builds that do not require narrow-phase collision detection.   

_<sup>1</sup> Added  v3.0.1_   

## Check Discussions & Release Notes, as well as Documentation on

https://github.com/selimanac/defold-daabbcc/discussions
https://github.com/selimanac/defold-daabbcc/wiki

