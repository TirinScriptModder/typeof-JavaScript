**value.toString();<br>Object.prototype.toString.call(value);<br>typeof value;<br>**
**結果**
<table>
<tr>
<th>value=</th>
<th>Array()</th>
<th>Boolean()</th>
<th>Function()</th>
</tr>
<tr>
<th>value.toString()</th>
<th>-</th>
<th>false</th>
<th>function anonymous(){}</th>
</tr>
<tr>
<th>Object.prototype.toString.call(value)</th>
<th>[object Array]</th>
<th>[object Boolean]</th>
<th>[object Function]</th>
</tr>
<tr>
<th>typeof value</th>
<th>object</th>
<th>boolean</th>
<th>function</th>
</tr>
</table>
<table>
<tr>
<th>value=</th>
<th>Number()</th>
<th>Object()</th>
<th>String()</th>
</tr>
<tr>
<th>value.toString()</th>
<th>0</th>
<th>[object Object]</th>
<th>-</th>
</tr>
<tr>
<th>Object.prototype.toString.call(value)</th>
<th>[object Number]</th>
<th>[object Object]</th>
<th>[object String]</th>
</tr>
<tr>
<th>typeof value</th>
<th>number</th>
<th>object</th>
<th>string</th>
</tr>
</table>
<table>
<tr>
<th>value=</th>
<th>Symbol()</th>
<th>null</th>
<th>undefined</th>
</tr>
<tr>
<th>value.toString()</th>
<th>error</th>
<th>error</th>
<th>error</th>
</tr>
<tr>
<th>Object.prototype.toString.call(value)</th>
<th>[object Symbol]</th>
<th>[object Null]</th>
<th>[object Undefined]</th>
</tr>
<tr>
<th>typeof value</th>
<th>symbol</th>
<th>object</th>
<th>undefined</th>
</tr>
</table>
