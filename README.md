# Restock-monitoring

来点大佬pr完善一下，没人pr就将就用

集成telegram，用于补货监控推送，快黑五了，速速用起来！

可以把上述两个文件打包放在/root/monitor/商家名字/路径下，方便管理


检查进程
```
ps -ef | grep python
```

常驻命令
```
nohup python3 /root/monitor/商家名字/monitor.py &
```

临时命令
```
python3 /root/monitor/buyvm/monitor.py
```

删除文件锁
```
rm /tmp/monitor_script.lock
```
