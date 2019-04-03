
在安装过程中，要运行 `pip install -r requirements.txt` 

这里会因为 psycopg2 而报错，此时修改 requirements.txt如下：


```
#psycopg2>=2.7,<2.8 --no-binary psycopg2
psycopg2==2.7.7 --no-binary psycopg2
```
