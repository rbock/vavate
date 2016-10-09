all
=======
This is the task:

```
template <bool... Args>
struct all_t
{
    static constexpr bool value = (true if all Args are true);
};
```

