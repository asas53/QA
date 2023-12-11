<!DOCTYPE html>
<html>
<head>
    <title>賭博默示錄</title>
</head>
<body>
    <h1>賭博默示錄</h1>
    <input type="text" id="query" placeholder="請輸入您想查詢的東西(例如:給開司一罐啤酒!">
    <button onclick="search()">Search</button>
    <h3>請輸入您想查詢的東西(例如:給開司一罐啤酒!</h3>
    <p id="result"></p>

    <script>
        function search() {
            var query = document.getElementById('query').value;
            var url = 'https://script.google.com/macros/s/AKfycbxVvhiZboiKE0XACTaJGLrGFcqcx4WTN2ZMB125_SJk12_cmhQ0c3uvqS-WvGo3luLh/exec' + encodeURIComponent(query);

            fetch(url)
                .then(response => response.text())
                .then(text => document.getElementById('result').innerText = text)
                .catch(error => console.error('Error:', error));
        }
    </script>
</body>
</html>
