# Java

# 日本語

#### OutofMemory

```
┌─────────────────────────────────────┐┌───────────┐
│ Heap                                ││ Native    │
│┌────────────────────────────┐┌─────┐││           │
││ Young                      ││ Old │││           │
││┌──────────────────────────┐││     │││           │
│││ Eden                     │││     │││           │
││└──────────────────────────┘││     │││           │
││┌────────────┐┌────────────┐││     │││           │
│││ Supervivor ││ Supervivor │││     │││           │
││└────────────┘└────────────┘││     │││           │
│└────────────────────────────┘└─────┘││           │
└─────────────────────────────────────┘└───────────┘
```


* http://qiita.com/opengl-8080/items/64152ee9965441f7667b#参考
