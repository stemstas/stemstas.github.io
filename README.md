<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Таблица 4x5</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid black;
            padding: 8px;
            text-align: center;
        }
        th {
            background-color: #f2f2f2;
        }
        td:first-child,
        th:first-child {
            background-color: #d3d3d3; 
            font-weight: bold; 
        }
        tr:first-child th {
            background-color: #d3d3d3; 
            font-weight: bold; 
        }
        a {
            color: blue; 
            text-decoration: none; 
        }
        .red-text {
            color: red; 
        }
    </style>
</head>
<body>
    <h1>Таблица 4x5</h1>
    <table>
        <thead>
            <tr>
                <th></th> 
                <th>Simple</th>
                <th>Continuous</th>
                <th>Perfect</th>
                <th>Perfect Continuous</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Present</td> 
                <td><a href="present simple.html">Present Simple</a></td>
                <td><a href="present continuous.html">Present Continuous</a></td>
                <td><a href="present perfect.html">Present Perfect</a></td>
                <td><a href="present perfect continuous.html" class="red-text">Present Perfect Continuous</a></td>
            </tr>
            <tr>
                <td>Past</td> 
                <td><a href="past simple.html">Past Simple</a></td>
                <td><a href="past continuous.html" class="red-text">Past Continuous</a></td>
                <td><a href="past perfect.html" class="red-text">Past Perfect</a></td>
                <td><a href="past perfect continuous.html" class="red-text">Past Perfect Continuous</a></td>
            </tr>
            <tr>
                <td>Future</td> 
                <td><a href="future simple.html">Future Simple</a></td>
                <td><a href="future continuous.html" class="red-text">Future Continuous</a></td>
                <td><a href="future perfect.html" class="red-text">Future Perfect</a></td>
                <td><a href="future perfect continuous.html" class="red-text">Future Perfect Continuous</a></td>
            </tr>
        </tbody>
    </table>
</body>
</html>
