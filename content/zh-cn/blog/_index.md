---
date: "2025-06-24T23:03:00+08:00"
draft: true
title: "Blog"
type: docs
---

## 图片使用

![](/images/logo.jpg)
![风景](https://picsum.photos/800/600)
![风景](https://picsum.photos/800/600 "Unsplash 风景")

## 图标使用

[icon link ](https://v1.heroicons.com/)

{{< icon "github" >}}

{{< icon "academic-cap" >}}

## 提示使用

> [!NOTE]
> 用户应该知道的有用信息，即使是在浏览内容时。

> [!TIP]
> 帮助用户更好地或更轻松地完成任务的建议。

> [!IMPORTANT]
> 用户需要了解的关键信息，以实现他们的目标。

> [!WARNING]
> 需要用户立即注意的紧急信息，以避免问题。

> [!CAUTION]
> 关于某些操作的风险或负面结果的建议。

## 代码使用

`this is shell code`

```python {filename="hello.py"}
def say_hello():
    print("Hello!")
```

```go {base_url="https://github.com/imfing/hextra/blob/main/",filename="exampleSite/hugo.work"}
go 1.20
```

```python {linenos=table,hl_lines=[2,4],linenostart=1,filename="hello.py"}
def say_hello():
    print("Hello!")

def main():
    say_hello()
```

## 步骤使用

{{% steps %}}

### 第一步

这是第一步。

### 第二步

这是第二步。

{{% /steps %}}
