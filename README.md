## 构建
```
helm package .
helm lint .
```

## 安装
```
helm repo add tcss https://fxm5547.github.io/tcss-chart
helm install tcss tcss/tcss-chart --set appid=$appid --set token=$appid --set vip=$vip --set k8s_name=$k8sname
```
