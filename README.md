# TinyTimer
A quick header only timer C++ implementation.

## How to use:
```
#include <Timer.hpp>

...
Timer<int> t;
t.start();
/* Do something */
auto ms = t.milliseconds_elapsed();
...

```

## Install

This is a header only implementation. Simply include the file in your project. It should compile just fine if you are using C++11 or higher.
