# 智能识别收货地址
预览地址https://wzc570738205.github.io/boke/smartparse.html

## 执行parse之前必须操作一次parseArea生成专用数据

## 数据来源(如有更新请更新此js)
```
area-list.js
```
## 支持以下数据格式

1. 马云,1351111111,北京市朝阳区姚家园3楼
2. 马云1351111111北京市朝阳区姚家园3楼
3. 北京市朝阳区姚家园3楼1351111111马云
4. 北京市朝阳区姚家园3楼150-0000-0000马云

## 生成数据格式
```
{
addr: "姚家园3楼"
area: "朝阳区"
city: "北京"
detail: ""
mobile: "15000000000"
name: "马云"
phone: ""
province: "北京"
result: undefined
zip_code: ""
}
```

