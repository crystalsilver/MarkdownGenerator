**STRUCT**
# `MarkdownLink`

**Contents**
- [Properties](#properties)
  - `text`
  - `url`
  - `markdown`
- [Methods](#methods)
  - `init(text:url:)`

**Declaration**
```swift
public struct MarkdownLink: MarkdownConvertible
```



> Render an HTML link in Markdown format
>
>     MarkdownLink(text: "Google", url: "https://example.com").markdown
>
> Would render as:
>
>     [Google](https://example.com)

## Properties
### `text`

**Declaration**
```swift
public let text: String
```



> Text to display as hyper-linked.

### `url`

**Declaration**
```swift
public let url: String
```



> Link URL, can be absolute, relative, or #local.

### `markdown`

**Declaration**
```swift
public var markdown: String
```



> Generated Markdown output

## Methods
### `init(text:url:)`

**Declaration**
```swift
public init(text: String, url: String)
```



> MarkdownLink initializer
>
> - Parameters:
>   - text: Text to display as hyper-linked.
>   - url: Link URL, can be absolute, relative, or #local.

#### Parameters
| Name | Description |
| ---- | ----------- |
| text | Text to display as hyper-linked. |
| url | Link URL, can be absolute, relative, or #local. |