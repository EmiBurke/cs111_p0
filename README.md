# A Kernel Seedling
TODO: intro
Proggggrammm coooountttts thhhe processes running.

## Building
```shell
TODO: cmd for build
```
make ----- commands    to ruuuun innn the shell   to bbbuilllld
sudo insmod proc_count.c

## Running
```shell
TODO: cmd for running binary
```
TODO: results?

cd /proc/
cat count

result: number of processes

## Cleaning Up
```shell
TODO: cmd for cleaning the built binary
```

rmmod proc_count

## Testing
```python
python -m unittest
```
TODO: results?

All the tests passed. It correctly shows the number of processes.

Report which kernel release version you tested your module on
(hint: use `uname`, check for options with `man uname`).
It should match release numbers as seen on https://www.kernel.org/.

```shell
uname -r -s -v
```
TODO: kernel ver
Linux 5.14.8-arch1-1 #1 SMP PREEMPT Sun, 26 Sep 2021 19:36:15 +0000
