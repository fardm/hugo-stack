---
draft: true
---
## image
figure
```
{{<figure src="/post/img/filename.jpg" width="80%" >}}
```

markdown
```
![image](post/img/filename.jpg)
```

Hyperlink
```
[![image](post/img/filename.jpg)](https://site.com)
```
## link
link to note
```
[text]({{< ref "file name" >}})
```

link to heading
```
[text]({{< ref "file name#title heading" >}})
```

## Templater

```
<% tp.file.folder() %>
```

```
<% tp.file.title %>
```

## Obsidian to Hugo

### google drive
```
python -m obsidian_to_hugo --obsidian-vault-dir="C:\Users\Arvin\My Drive\obsidian\My Note\Publish\post" --hugo-content-dir=C:\mysite\ifard\content\post
```

📁 ifard:  [open folder](file:\\\C:\mysite\ifard\content\post)


```
python -m obsidian_to_hugo --obsidian-vault-dir=C:\Users\Arvin\Desktop\a --hugo-content-dir=C:\Users\Arvin\Desktop\b
```
