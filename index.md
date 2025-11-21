# A
## B
### C
#### D
##### E
###### F

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

```cpp
template <typename T, typename... Args> void inline logger_helper(
    std::ostringstream& oss,
    const T& first,
    const Args&... rest
) {
    //-- Process First Argument
    processArgument(oss, first);
    //-- Recursively Process Remaining Arguments
    logger_helper(oss, rest...);
}
```
- [ ] Turn on GitHub Pages
- [ ] Outline my portfolio
- [ ] Introduce myself to the world
