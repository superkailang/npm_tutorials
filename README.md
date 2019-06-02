# npm_tutorials

## 常见的Bug集合


### npm EACCES: permission denied

##### linux上安装好nodejs后,使用npm install命令安装项目相关依赖一直都报permission denied权限


#### 解决办法 ,需要这个命令。
```
npm install --unsafe-perm=true --allow-root -X XXXX
```


