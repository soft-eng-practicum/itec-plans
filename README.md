# itec-plans : a landing place for dependency graphs

We use `graphviz` to convert our course dependency chains in different ITEC tracks to directed graphs.

# Steps
Generate directed graphs with:

```bash
$ cd AY19-20
$ dot -Tpdf DataScienceAndAnalytics.dot -o outputs/DataScienceAndAnalytics.pdf
$ dot -Tpdf DigitalMedia.dot -o outputs/DigitalMedia.pdf
$ dot -Tpdf EnterpriseSystems.dot -o outputs/EnterpriseSystems.pdf
$ dot -Tpdf SoftwareDevelopment.dot -o outputs/SoftwareDevelopment.pdf
$ dot -Tpdf SystemsSecurity.dot -o outputs/SystemsSecurity.pdf
```

or simply

```bash
$ cd AY19-20
$ ./build.zsh
```

Please see the `outputs` folder for the generated graphs.

# Latest program plans 

Also see [past](PAST.md) and proposed [future changes](CHANGES.md).

## Data Science and Analytics (updated AY20-21, also see [proposed changes](CHANGES.md))

Manual:
[PDF link](AY20-21/manual/DSA-mindmup-fa2019-ITEC4000.pdf)
![Data Science and Analytics](AY20-21/manual/DSA-mindmup-fa2019-ITEC4000.png)

Graphviz:
[PDF link](AY20-21/outputs/DataScienceAndAnalytics.pdf)
![Data Science and Analytics](AY20-21/outputs/DataScienceAndAnalytics.png)

## Digital Media (updated AY20-21)

[PDF link](AY20-21/outputs/DigitalMedia.pdf)
![Digital Media](AY20-21/outputs/DigitalMedia.png)


## Enterprise Systems (no change since AY19-20)

[PDF link](AY20-21/outputs/EnterpriseSystems.pdf)
![Enterprise Systems](AY20-21/outputs/EnterpriseSystems.png)

## Software Development (updated AY20-21)

![Software Development](AY20-21/outputs/SoftwareDevelopment.png)

## Systems Security (no change since AY19-20)

[PDF link](AY20-21/outputs/SystemsSecurity.pdf)
![Systems Security](AY20-21/outputs/SystemsSecurity.png)
