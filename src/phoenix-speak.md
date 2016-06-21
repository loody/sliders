# 菲尼克斯如是说

author: 马陆骋 <malucheng@boohee.com>

## 关于 Phoenix

- Server-side web framework (similar to rails)
- 创始人是 Rails 核心成员
- 基于 Elixir （语法非常类似 Ruby 的函数式编程语言，基于 Erlang 虚拟机）

### Rails 背景

Elixir’s creator José Valim was a member of the Rails core team

and Chris also comes from a Rails background.

### 函数式编程

- Elixir is a mostly pure functional programming language.
- Elixir has no objects

## 与 Rails 的主要区别

- Changeset
- Repository
- View Model

## 路由

router 层就可以进行 filter 的配置, 而不是使用 controller 的继承

TODO code example

## 参数处理

Strong Parameter VS changeSet

TODO username example

## 储存

仓库模式(类 Data Mapper) vs ActiveRecord

TODO easy to test without migration example

## 视图模型

分离 View 和 Template

TODO title example

## 可以学到的东西

- 单一职责 (same logic with more space to put)
- 封装实现细节
- 只因一个原因改变

## 目前的问题

客户端请求参数多样

需要的返回值也很多样

数据的存储不是很统一, 持久化方式也很多样

## 给我的启发

1. 使用 changeset 封装请求参数, 进行过滤和重构
2. 使用 view model 分离不同的返回类型(容易测试)
3. 使用 Repository 模式封装持久化层的具体细节

TODO graph flow
