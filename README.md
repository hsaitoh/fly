# fly
* pipelineの情報出力
```
fly -t target名 get-pipeline -p pipeline名
```

* ハイジャック
```
fly -t target名 hijack -j pipeline名/job名 -b 通番
```
