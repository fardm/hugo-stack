---
draft: true
---
## image
```
{{<figure src="/post/img/filename.jpg" width="80%" >}}
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
python -m obsidian_to_hugo --obsidian-vault-dir="C:\Users\Arvin\My Drive\obsidian\Publish\post" --hugo-content-dir=C:\mysite\ifard\content\post
```



