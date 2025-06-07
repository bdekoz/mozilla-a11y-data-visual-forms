
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Data Report from JSON</title>
    <!-- Basic styling for the table -->
    <style>
        body {
            font-family: 'Inter', sans-serif;
            margin: 2rem;
            background-color: #f7f7f7;
            color: #333;
        }
        h1 {
            color: #2c3e50;
            text-align: center;
            margin-bottom: 1.5rem;
        }
        .table-container {
            margin: 2rem auto;
            max-width: 90%;
            overflow-x: auto; /* Allows horizontal scrolling on small screens */
            border-radius: 0.5rem;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            background-color: #ffffff;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            text-align: left;
            border-radius: 0.5rem; /* Rounded corners for the table */
        }
        th, td {
            padding: 0.75rem 1rem;
            border-bottom: 1px solid #e2e8f0;
            white-space: nowrap; /* Prevent content from wrapping */
        }
        th {
            background-color: #edf2f7;
            font-weight: 600;
            color: #4a5568;
            text-transform: uppercase;
            font-size: 0.875rem;
        }
        tr:last-child td {
            border-bottom: none;
        }
        tbody tr:hover {
            background-color: #f0f4f8; /* Light hover effect */
        }
        /* Specific rounded corners for first/last cells */
        table thead tr:first-child th:first-child { border-top-left-radius: 0.5rem; }
        table thead tr:first-child th:last-child { border-top-right-radius: 0.5rem; }
        table tbody tr:last-child td:first-child { border-bottom-left-radius: 0.5rem; }
        table tbody tr:last-child td:last-child { border-bottom-right-radius: 0.5rem; }
    </style>
</head>
<body>
    <h1>Index</h1>

    <div class="table-container">
        <table border="1" class="dataframe min-w-full divide-y divide-gray-200 shadow-md rounded-lg overflow-hidden">
  <thead>
    <tr style="text-align: right;">
      <th>name</th>
      <th>age</th>
      <th>city</th>
      <th>occupation</th>
      <th>salary</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Alice Johnson</td>
      <td>30</td>
      <td>New York</td>
      <td>Software Engineer</td>
      <td>95000.75</td>
    </tr>
    <tr>
      <td>Bob Williams</td>
      <td>24</td>
      <td>Los Angeles</td>
      <td>Graphic Designer</td>
      <td>62500.50</td>
    </tr>
    <tr>
      <td>Charlie Brown</td>
      <td>35</td>
      <td>Chicago</td>
      <td>Project Manager</td>
      <td>110000.00</td>
    </tr>
    <tr>
      <td>Diana Prince</td>
      <td>29</td>
      <td>London</td>
      <td>Data Scientist</td>
      <td>88000.20</td>
    </tr>
  </tbody>
</table>
    </div>
</body>
</html>
        