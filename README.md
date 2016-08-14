# Simplate

> A Simple JavaScript Template Engine.

## Get Started

### Grammar

**Evaluate（过程控制）**

```
{{ for ( var item in data ) { }}
  Some code here...
{{ } }}
```

**Interpolate（输出控制）**

```
{{= data.name }}
```

**Comment（代码注释）**

```
{{# Some comments here... }}
```

## TODO

**NonEscape（非编码输出）**

```
{{! data.url }}
```

**ErrorHandler**

**...**

## Update Logs

### v0.1.0

- 完成了模板基本架构
- 实现了基础功能 `evaluate` 和 `interpolate`
- 添加了功能 `comment` 


## License

Released under the [MIT](https://github.com/Phantr4x/Simplate/blob/master/LICENSE) License

© Phantr4x
