# 分析binlog利器
```shell
python binlog2sql.py -h127.0.0.1 -P3306 -uroot -p'xxxxx' -d db -t table start-datetime='2021-02-23 00:00:00' --start-file='binlog-name' > output.log
```

输出 sql语句 # 开始pos号，结束pos号 执行时间
```sql
INSERT INTO `db`.`table`(x,x,x,x) VALUES (x,x,x,x); #start 1047973405 end 1048057040 time 2021-02-22 22:32:01
```
