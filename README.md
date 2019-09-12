# s3bmarkrandom

Built from https://github.com/dvassallo/s3-benchmark
Originally created ‘empty’ object payload (all ‘0’ )

Modified 'main.go' with these edits
```
Line #20: Import “math/rand”
#120: //JTH removed - cleanup()
#244: rand.Seed(time.Now().UnixNano())
#289: rand.Read(payload)
```
