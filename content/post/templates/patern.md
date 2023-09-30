---
draft: true
---
## image
```
{{<figure src="/post/img/filename.jpg" width="80%" >}}
```

## link

```
[text]({{< ref "file name" >}})
```

## Templater

```
<% tp.file.folder() %>
```

```
<% tp.file.title %>
```

## obsidian to hugo

```
python -m obsidian_to_hugo --obsidian-vault-dir=C:\Users\Arvin\OneDrive\Dokumenty\obsidian\Publish --hugo-content-dir=C:\mysite\blog\content\post
```
