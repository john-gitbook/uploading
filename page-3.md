# Page 3

|   Header 1   |   Header 2   | Header 3  | Header 4 |
| ------------ | ------------ | --------- | -------- |
| Row 1, Col 1 | Row 1, Col 2 | Row 1, Col 3 | Row 1, Col 4 |
| Row 2, Col 1 | Row 2, Col 2 colspan | colspan (merged into one cell) |
| <td colspan="2" rowspan="2">Multirow & Multicolumn</td> | Row 3, Col 3 | Row 3, Col 4 |
| | Row 4, Col 3 | Row 4, Col 4 |


<table>
  <tr>
    <th>Header 1</th>
    <th>Header 2</th>
    <th>Header 3</th>
    <th>Header 4</th>
  </tr>
  <tr>
    <td>Row 1, Col 1</td>
    <td>Row 1, Col 2</td>
    <td>Row 1, Col 3</td>
    <td>Row 1, Col 4</td>
  </tr>
  <tr>
    <td>Row 2, Col 1</td>
    <td colspan="2">Row 2, Col 2 & 3 (colspan)</td>
    <td>Row 2, Col 4</td>
  </tr>
  <tr>
    <td rowspan="2">Row 3 & 4, Col 1 (rowspan)</td>
    <td>Row 3, Col 2</td>
    <td>Row 3, Col 3</td>
    <td>Row 3, Col 4</td>
  </tr>
  <tr>
    <td>Row 4, Col 2</td>
    <td colspan="2">Row 4, Col 3 & 4 (colspan)</td>
  </tr>
</table>
