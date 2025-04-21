# Project_Html
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .widget{
            border: 1px solid #657002;
            border-radius: 10px;
            margin: 10px;
            padding: 10px;
            width: 300px;
            background-color: #11da5e;
        }
        .widget-header{
            background-color: #b1e99c;
            padding: 5px;
            border-bottom: 1px solid #ccc;
            margin-bottom: 10px;
            border-radius: 10px;
        }
        .widget-header h3{
            margin: 0;
            font-size: 1.2em;
            font-style: italic;
            text-align: center;
        }
        .widget-content{
            padding: 10px;
            font-size: 17px;
            text-align: center;
        }
        .widget-footer{
            text-align:center;
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <div class="widget">
        <div class="widget-header">
            <h3>عنوان</h3>
        </div>
        <div class="widget-content">
            <p>این یک ویجت است</p>
        </div>
        <div class="widget-footer">
            <button id="update-button">آپدیت</button>
        </div>
    </div>
</body>
</html>
