# Sript Utilities

## CMD_log (CentOS & Ubuntu)
```sh 
curl -Lso- https://raw.githubusercontent.com/uncelvel/scripts/master/Utilities/cmdlog.sh | bash
```

## Create Swap
```sh 
curl -Lso- https://raw.githubusercontent.com/uncelvel/scripts/master/Utilities/create_swap.sh <size> | bash
```

- Lưu ý: `<size>` chính là size swap (GB)

## Benchmark
```sh 
curl -Lso- https://raw.githubusercontent.com/uncelvel/scripts/master/Utilities/bench_vm.sh | bash
```


## Force Update time for Linux 
```sh 
sudo date -s "$(wget -qSO- --max-redirect=0 google.com 2>&1 | grep Date: | cut -d' ' -f5-8)Z"
```
