## Functions

<dl>
<dt><a href="#getAllFileNameFromDir">getAllFileNameFromDir(dirPath)</a> ⇒ <code>array</code></dt>
<dd><p>获取文件夹下所有文件名</p>
</dd>
<dt><a href="#copyFile">copyFile(from, to)</a></dt>
<dd><p>复制文件</p>
</dd>
<dt><a href="#getProcessParams">getProcessParams()</a> ⇒ <code>array</code></dt>
<dd><p>获取 node 程序参数</p>
</dd>
<dt><a href="#getFileExt">getFileExt(fileName)</a> ⇒ <code>string</code></dt>
<dd></dd>
<dt><a href="#getFileNameOnly">getFileNameOnly(filePath)</a></dt>
<dd><p>通过文件路径仅获取文件名</p>
</dd>
<dt><a href="#runShellCommand">runShellCommand(command, shell)</a></dt>
<dd><p>执行 shell 命令</p>
</dd>
<dt><a href="#isSameFile">isSameFile(pathA, pathB)</a></dt>
<dd><p>比对两个文件（如json）（格式和内容）是否全等</p>
</dd>
<dt><a href="#isDir">isDir(path)</a> ⇒ <code>boolean</code></dt>
<dd><p>判断是否文件夹</p>
</dd>
<dt><a href="#getSystemName">getSystemName()</a> ⇒ <code>string</code></dt>
<dd><p>获取操作系统名，可能是 MacOS、Linux、Windows</p>
</dd>
<dt><a href="#createDirIfNonExist">createDirIfNonExist(filepath)</a> ⇒ <code>boolean</code></dt>
<dd><p>如果不存在则创建文件夹</p>
</dd>
<dt><a href="#normalizePath">normalizePath(filepath)</a> ⇒ <code>string</code></dt>
<dd><p>把路径格式化为 xx/xx，主要是为了处理 win系统上的差异</p>
</dd>
</dl>

<a name="getAllFileNameFromDir"></a>

## getAllFileNameFromDir(dirPath) ⇒ <code>array</code>
获取文件夹下所有文件名

**Kind**: global function  
**Returns**: <code>array</code> - 文件名列表  

| Param | Type | Description |
| --- | --- | --- |
| dirPath | <code>string</code> | 文件夹路径 |

<a name="copyFile"></a>

## copyFile(from, to)
复制文件

**Kind**: global function  

| Param | Type | Description |
| --- | --- | --- |
| from | <code>string</code> | 复制文件路径 |
| to | <code>string</code> | 目标文件路径 |

<a name="getProcessParams"></a>

## getProcessParams() ⇒ <code>array</code>
获取 node 程序参数

**Kind**: global function  
**Returns**: <code>array</code> - 参数列表  
<a name="getFileExt"></a>

## getFileExt(fileName) ⇒ <code>string</code>
**Kind**: global function  
**Returns**: <code>string</code> - 返回文件名后缀  

| Param | Type | Description |
| --- | --- | --- |
| fileName | <code>string</code> | 带后缀的文件名 |

<a name="getFileNameOnly"></a>

## getFileNameOnly(filePath)
通过文件路径仅获取文件名

**Kind**: global function  

| Param | Type | Description |
| --- | --- | --- |
| filePath | <code>string</code> | 文件绝对路径 |

<a name="runShellCommand"></a>

## runShellCommand(command, shell)
执行 shell 命令

**Kind**: global function  

| Param | Type | Description |
| --- | --- | --- |
| command | <code>string</code> | 命令 |
| shell | <code>string</code> | 选填，shell类型 |

<a name="isSameFile"></a>

## isSameFile(pathA, pathB)
比对两个文件（如json）（格式和内容）是否全等

**Kind**: global function  

| Param | Type | Description |
| --- | --- | --- |
| pathA | <code>string</code> | 文件A，绝对路径 |
| pathB | <code>string</code> | 文件B，绝对路径 |

<a name="isDir"></a>

## isDir(path) ⇒ <code>boolean</code>
判断是否文件夹

**Kind**: global function  
**Returns**: <code>boolean</code> - 是否为文件夹  

| Param | Type | Description |
| --- | --- | --- |
| path | <code>string</code> | 文件夹绝对路径 |

<a name="getSystemName"></a>

## getSystemName() ⇒ <code>string</code>
获取操作系统名，可能是 MacOS、Linux、Windows

**Kind**: global function  
**Returns**: <code>string</code> - 系统名  
<a name="createDirIfNonExist"></a>

## createDirIfNonExist(filepath) ⇒ <code>boolean</code>
如果不存在则创建文件夹

**Kind**: global function  
**Returns**: <code>boolean</code> - 完成则返回true  

| Param | Type | Description |
| --- | --- | --- |
| filepath | <code>string</code> | 文件夹绝对路径 |

<a name="normalizePath"></a>

## normalizePath(filepath) ⇒ <code>string</code>
把路径格式化为 xx/xx，主要是为了处理 win系统上的差异

**Kind**: global function  
**Returns**: <code>string</code> - 格式化后的路径  

| Param | Type | Description |
| --- | --- | --- |
| filepath | <code>string</code> | 文件路径 |

