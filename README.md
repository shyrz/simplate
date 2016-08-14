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

**NonEscape（非编码输出）**

```
{{! data.url }}
```

**Comment（代码注释）**

```
{{# Some comments here... }}
```

## TODO

1. `errorHandler()`

2. Use `with() {}`

3. ...

## Update Logs

### v0.1.0

- 完成了模板基本架构
- 实现了基础功能 `evaluate` 和 `interpolate`
- 添加了功能 `comment`

### v0.1.1

- 添加了功能 `nonEscape`

## License

Released under the [MIT](https://github.com/Phantr4x/Simplate/blob/master/LICENSE) License

© Phantr4x
