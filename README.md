# CodesSnippet ios常用代码片段
##工程
### 获取标准 .gitignore

~~~bash
curl -o .gitignore https://www.gitignore.io/api/objective-c
~~~

### Swift Log

~~~swift
func printLog<T>(message: T,
                    file: String = #file,
                  method: String = #function,
                    line: Int = #line)
{
    #if DEBUG
    print("\((file as NSString).lastPathComponent)[\(line)], \(method): \(message)")
    #endif
}
~~~

### 常用 Xcode 路径

~~~bash
# Provisioning Profiles 路径：
~/Library/MobileDevice/Provisioning Profiles

# Xcode 插件路径：
~/Library/Application Support/Developer/Shared/Xcode/Plug-ins

# code snippet：
~/Library/Developer/Xcode/UserData/CodeSnippets

# derived data:
~/Library/Developer/Xcode/DerivedData
~~~

### 常用命令行工具

~~~bash
# 复制文档内容到剪切板
pbcopy < hello.txt
~~~
