### biopython
---
https://biopython.org/

```py
AlignIO.read(open("PF09395_seed.sth"), "stockholm")
print(alignment.format("fasta"))

from Bio import AlignIO

input_handle = open("example.phy", "rU")
output_handle = open("example.sth", "w")

alignments = AlignIO.parse(input_handle, "phylip")
AlignIO.write(alignments, output_handle, "stockholm")

output_handle.close()
input_handle.close()
```

```
```

```
```


