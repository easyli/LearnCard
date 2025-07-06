React Native

<table>
<tr>
<th>function description</th>
<th>example</th>
</tr>
<tr>
<td>Dynamic Imports</td>
<td>

```tsx
const package = await import('package'); 
package.function()
```

</td>
</tr>

<tr>
<td>Class Fields</td>
<td>

```tsx
class Bork {
    static a = 'foo'; 
    static b; 
    x = 'bar'; 
    y;
 }
```

</td>
</tr>

</table>

table from [JavaScript Syntax Transformers](https://reactnative.dev/docs/javascript-environment)