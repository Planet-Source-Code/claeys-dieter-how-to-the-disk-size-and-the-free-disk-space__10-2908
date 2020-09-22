<div align="center">

## How to the disk size and the free disk space?


</div>

### Description

How to the disk size and the free disk space?

RATE MY CODE, PLEASE...
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Claeys Dieter](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/claeys-dieter.md)
**Level**          |Beginner
**User Rating**    |3.8 (30 globes from 8 users)
**Compatibility**  |C\#
**Category**       |[System Services/ Functions](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/system-services-functions__10-23.md)
**World**          |[\.Net \(C\#, VB\.net\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/net-c-vb-net.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/claeys-dieter-how-to-the-disk-size-and-the-free-disk-space__10-2908/archive/master.zip)





### Source Code

<style type="text/css">
<!--
.style11 {font-family: Arial, Helvetica, sans-serif; font-size: 10; font-weight: bold; }
.style13 {font-family: Verdana, Arial, Helvetica, sans-serif; font-size: 12px; }
.style23 {font-family: Verdana, Arial, Helvetica, sans-serif; font-size: 12px; font-weight: bold; }
-->
</style>
<p><BR>
 <BR>
 <BR>
 <BR>
 <BR>
 <BR>
 <BR>
 <BR>
<BR>
<BR>
<BR>
<BR>
</p>
<table width="612" border="0">
 <tr>
 <td width="538" class="style23"><span class="style13">using System;</span></td>
 </tr>
 <tr>
 <td class="style23">using System.Management; </td>
 </tr>
 <tr>
 <td class="style23">... </td>
 </tr>
 <tr>
 <td class="style23">ManagementObject disk = new </td>
 </tr>
 <tr>
 <td class="style23">ManagementObject("win32_logicaldisk.deviceid="c:""); </td>
 </tr>
 <tr>
 <td class="style23">disk.Get();</td>
 </tr>
 <tr>
 <td class="style23">Console.WriteLine("Logical Disk Size = " + disk["Size"] + " bytes"); </td>
 </tr>
 <tr>
 <td class="style23">Console.WriteLine("Logical Disk FreeSpace = " + disk["FreeSpace"] + " <br>
bytes"); </td>
 </tr>
 <tr>
 <td class="style23"> </td>
 </tr>
 <tr>
 <td class="style23"> </td>
 </tr>
</table>
<p> </p>
</html>

