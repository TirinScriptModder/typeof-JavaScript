<table>
<tr>
<th>value=</th>
<th>new Array()</th>
<th>new Boolean()</th>
<th>new Function()</th>
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
<th>new value=</th>
<th>new Number()</th>
<th>new Object()</th>
<th>new String()</th>
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
<th>null</th>
<th>undefined</th>
</tr>
<tr>
<th>value.toString()</th>
<th>error</th>
<th>error</th>
</tr>
<tr>
<th>Object.prototype.toString.call(value)</th>
<th>[object Null]</th>
<th>[object Undefined]</th>
</tr>
<tr>
<th>typeof value</th>
<th>object</th>
<th>undefined</th>
</tr>
</table>
