# 百度蜘蛛访问监控台

分析服务器访问日志中的百度蜘蛛与其他搜索引擎爬虫记录，查看抓取趋势、状态码、响应耗时和异常 URL。

## 核心功能
- 统计 Baiduspider 访问量与访问页面
- 汇总 2xx、3xx、4xx、5xx 状态码
- 发现慢响应、错误页面和异常重定向
- 支持 CSV 输入与 JSON 输出

## 使用
```powershell
python tool.py --demo
python tool.py --input sample.csv --json
```
CSV 需要包含 `url,status,user_agent,ms` 四列。本项目分析真实日志，不伪造蜘蛛身份或虚构访问。

官网：https://jta.mobi  
QQ群：1039545483

## 许可证
MIT License
