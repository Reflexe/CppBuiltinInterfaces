# keywords
    - `extends`
    - `implements`
    - `interface`
    
    
# `interface`
- Automaticlly have a pure virtual destructor.
- Shall not have any members
- Might have pure virtual members. 

Example:
```cpp
interface Interface {
    void pureFunction();

}
```

or in vanilla cpp:

```cpp
class Interface {
    virtual void pureFunction() = 0;
    
    virtual ~Interface() = 0;
};
```

# `extends`:
```cpp
class <class name> extends <Base class> {

};
```

# `implements`
```cpp
class <class name> implements <interface name> {

};

