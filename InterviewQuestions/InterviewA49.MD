## 49. Чем отличается wait(500) от sleep(500)?

```
sleep(500) вызывается у нити, wait(500) вызывается внутри синхронизированного блока у объекта, 
по которому данный блок синхронизирован. 

При вызове sleep(500) текущая нить будет ожидать 500 милисекунд, затем продолжит свою работу. 

При вызове wait(500) текущая нить снимет блокировку с синхронизированного объекта, и засыпает на 
500 миллисекунд. 
```