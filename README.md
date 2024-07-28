docker pull registry.cn-zhangjiakou.aliyuncs.com/pymvp/cj
docker run -d --restart=always --name=cj -p 5000:5000 registry.cn-zhangjiakou.aliyuncs.com/pymvp/cj
功能说明：
1./app 工作目录 可设置一天几次抽奖 可设置抽奖日期 可查询中奖数据(路由 /admin123) 包括导出数据 

