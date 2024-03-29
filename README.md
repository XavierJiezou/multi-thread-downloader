# Multi Thread Downloader

This is a Multi-thread downloader based on Python.

## Install

```bash
pip install requests tqdm
```

## Usage

```bash
git clone https://github.com/XavierJiezou/multi-thread-downloader.git
cd multi-thread-downloader
```

### Single thread

```bash
python temp.py
```

### Multi thread

```bash
python main.py
```

## Result

| Item          | Muti-thread | Single-thread |
|:-------------:|:-----------:|:-------------:|
| Total-time    | 93s         | 560s          |
| Average-speed | 9.06MB/s    | 1.50MB/s      |

## Todo

- [x] Multi-thread
- [ ] Resume work from the breakpoint
- [ ] GUI

## References

- [https://blog.csdn.net/qq_41488943/article/details/107118377](https://blog.csdn.net/qq_41488943/article/details/107118377)
- [https://requests.readthedocs.io/zh_CN/latest/user/quickstart.html#id9](https://requests.readthedocs.io/zh_CN/latest/user/quickstart.html#id9)
- [https://docs.python.org/zh-cn/3.8/library/concurrent.futures.html#threadpoolexecutor](https://docs.python.org/zh-cn/3.8/library/concurrent.futures.html#threadpoolexecutor)
