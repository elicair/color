# color
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Table with CSS Font</title>
    <style>
        /* Apply a clean sans-serif font to the whole table */
        table.custom-font-table {
            font-family: "Segoe UI", Arial, Helvetica, sans-serif;
            border-collapse: collapse;
            width: 60%;
            margin: 2em auto;
        }
        table.custom-font-table th,
        table.custom-font-table td {
            border: 1px solid #bbb;
            padding: 10px 16px;
            text-align: left;
        }
        table.custom-font-table th {
            background: #f4f7fa;
        }
        table.custom-font-table tr:nth-child(even) {
            background: #f8fbfc;
        }
    </style>
</head>
<head>
  <style>
    th {
      font-family: 'Arial', sans-serif;
    }
  </style>
</head>
</head>
<head>
<table border="1">
<tr>
<th style="background-color: white;">Header 1</th>
<th style="background-color: green; color: white;">Header 2</th>
<th style="background-color: blue; color: white;">Header 3</th>
<th style="background-color: grey; color: white;">Header 4</th>
</tr>
<tr>
<td>Row 1, Col 1</td>
<td>Row 1, Col 2</td>
<td>Row 1, Col 3</td>
<td>Row 1, Col 4</td>
</tr>
<tr>
<td>Row 2, Col 1</td>
<td>Row 2, Col 2</td>
<td>Row 2, Col 3</td>
<td>Row 2, Col 4</td>
</tr>
  <tr>
<td>Row 2, Col 1</td>
<td>Row 2, Col 2</td>
<td>Row 2, Col 3</td>
<td>Row 2, Col 4</td>
</tr>
</table>
