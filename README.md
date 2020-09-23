<div align="center">

## Easily Open a URL from your program\! \(MFC/VC\+\+\)


</div>

### Description

Lets you open a URL from any event in your MFC Applications with the ShellExecute API (Just like in VB!)
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Socketware\.net](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/socketware-net.md)
**Level**          |Unknown
**User Rating**    |5.0 (15 globes from 3 users)
**Compatibility**  |C\+\+ \(general\)
**Category**       |[Internet/ Browsers/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-browsers-html__3-9.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/socketware-net-easily-open-a-url-from-your-program-mfc-vc__3-10/archive/master.zip)





### Source Code

```
void OpenURL(void)
{
(32 >= (int)ShellExecute(NULL, "open", "http://www.socketware.net", NULL, NULL, SW_SHOWNORMAL));
}
// Very Simple : I can't think of anything usefull to post right now.
```

