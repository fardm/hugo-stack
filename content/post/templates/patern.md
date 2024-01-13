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

## obsidian to hugo

```
python -m obsidian_to_hugo --obsidian-vault-dir=C:\Users\Arvin\OneDrive\Dokumenty\obsidian\Publish --hugo-content-dir=C:\mysite\ifard\content\post
```


```
python -m obsidian_to_hugo --obsidian-vault-dir="C:\Users\Arvin\My Drive\obsidian\Publish" --hugo-content-dir=C:\mysite\ifard\content\post
```


python -m obsidian_to_hugo --obsidian-vault-dir="C:\Users\Arvin\Desktop\a" --hugo-content-dir="C:\Users\Arvin\Desktop\b"


python -m obsidian_to_hugo --obsidian-vault-dir=C:\Users\Arvin\OneDrive\Dokumenty\obsidian\Publish --hugo-content-dir=C:\mysite\ifard\content\post