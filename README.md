# dragonfly-decode

```
$ dragonfly-decode W1siZiIsIjIwMTQvMDMvMTAvMTAvNDUvMTkvOTUzL3FsbjJfcHJvZmlsZV9tNF8zLmpwZyJdLFsicCIsInRodW1iIiwiOTZ4PiIse31dLFsicCIsImNvbnZlcnQiLCItY29sb3JzcGFjZSBzUkdCIC1zdHJpcCIseyJmb3JtYXQiOiJqcGcifV1d
[["f", "2014/03/10/10/45/19/953/qln2_profile_m4_3.jpg"],
 ["p", "thumb", "96x>", {}],
 ["p", "convert", "-colorspace sRGB -strip", {"format"=>"jpg"}]]
$ cat found.txt 
W1siZiIsIjIwMTQvMDMvMTAvMTAvNDUvMTkvOTUzL3FsbjJfcHJvZmlsZV9tNF8zLmpwZyJdLFsicCIsInRodW1iIiwiOTZ4PiIse31dLFsicCIsImNvbnZlcnQiLCItY29sb3JzcGFjZSBzUkdCIC1zdHJpcCIseyJmb3JtYXQiOiJqcGcifV1d
$ dragonfly-decode found.txt 
[["f", "2014/03/10/10/45/19/953/qln2_profile_m4_3.jpg"],
 ["p", "thumb", "96x>", {}],
 ["p", "convert", "-colorspace sRGB -strip", {"format"=>"jpg"}]]
```
