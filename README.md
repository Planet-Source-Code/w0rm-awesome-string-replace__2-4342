<div align="center">

## AWESOME String Replace


</div>

### Description

To replace a word or characters in a string, using JavaScript.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[w0rm](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/w0rm.md)
**Level**          |Beginner
**User Rating**    |4.0 (8 globes from 2 users)
**Compatibility**  |
**Category**       |[String Manipulation](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/string-manipulation__2-60.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/w0rm-awesome-string-replace__2-4342/archive/master.zip)





### Source Code

```
function stringreplace(str,srchfor,rplwith){
	while (str.indexOf(srchfor)>-1) {
	 pos= str.indexOf(srchfor);
	 str = "" + (str.substring(0, pos) + rplwith + str.substring((pos + srchfor.length), str.length));
    }
   return str;
}
```

