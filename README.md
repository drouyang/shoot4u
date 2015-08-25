## Usage
### shoot4u
#### Option 1: with git
```
$ git am shoot4u-patch/*.patch
```
#### Option 2: with patch
```
$ patch -p1 < /path/to/dir/0001-*.patch
$ patch -p1 < /path/to/dir/0002-*.patch
```
### paravirtual remote TLB flush (pvtlb)
http://www.spinics.net/lists/kvm/msg78403.html

#### Option 1: with git
```
$ git am pvtlb-patch/pvtlb-linux-4.0.5-port/*.patch
```
#### Option 2: with patch
```
$ patch -p1 < /path/to/dir/0001-*.patch
$ patch -p1 < /path/to/dir/0002-*.patch
...
$ patch -p1 < /path/to/dir/0007-*.patch
```
