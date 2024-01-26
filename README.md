
# 领域驱动设计--基础设施层


## 缓存 - Normandy.Infrastructure.Cache 
支持Redis、MemoryCache缓存

## 配置 - Normandy.Infrastructure.Config
基于Microsoft.Extensions.Configuration的本地配置，支持本地加密配置

## DI容器 - Normandy.Infrastructure.DI
基于DependencyInjection的依赖注入

## SQL ORM - Normandy.Infrastructure.EntityFramework
基于EfCore的ORM注入

## Http请求工厂 - Normandy.Infrastructure.HttpClient
基于IHttpClientFactory的客户端请求工厂, 支持polly

## 定时任务 - Normandy.Infrastructure.JobSchedule
基于Quartz的定时任务

## 日志 - Normandy.Infrastructure.Log
基于Serilog的日志模块,支持自定义日志拦截器

## 属性映射 - Normandy.Infrastructure.Mapper
基于AutoMapper的属性映射

## Mongo ORM - Normandy.Infrastructure.Mongo
Mongo数据库操作相关

## TPL并行库 - Normandy.Infrastructure.TPL
基于ActionBlock的并行任务工作流

## 任意门工具集合 - Normandy.Infrastructure.Util
提供加密、序列化等工具类