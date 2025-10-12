Unity's IL2CPP headers: (here il2cpp-class-internals.h)
```c
typedef struct MethodInfo
{
// some pre-members
    Il2CppClass *klass;
// etc.
} MethodInfo;
```

😂 klass (to prevent name conflicts)
