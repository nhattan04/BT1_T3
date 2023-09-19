# BT1_T3
Tuần 3
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8" />
    <title></title>
    <style type="text/css">
        body {
            background-color: #CCCCCC;
            font-family: Arial, Helvetica, sans-serif;
        }

        #container {
            border: 2px solid #000000;
            width: 760px;
            background-color: #CCCCCC; /*Màu nền cho Container  SideBar*/
            margin: 0px auto; /*Canh giữa trang web*/
        }

        #banner {
            background-color: #EFEFEF;
            height: 100px;
        }

        #navigator {
            background-color: #999999;
            padding: 5px 0px;
            border-top: 2px solid black;
            border-bottom: 2px solid black;
        }

        #sidebar {
            width: 160px;
            float: left; /*phần SideBar bám (dock) vào bên trái */
        }

        #content {
            margin-left: 160px; /*phần lề trái của Content, bỏ đi chiều rộng của Sidebar*/
            min-height: 400px; /*chiều cao tối thiểu là 400px*/
            border-left: 2px solid black;
            background-color: #FFFFFF;
        }

        #footer {
            background-color: #999999;
            border-top: 2px solid black;
            text-align: center;
            padding: 5px 0px;
        }
    </style>

</head>
<body>
    <div id="container">
        <div id="banner">
            BANNER
        </div>
        <div id="navigator">
            NAVIGATOR
        </div>
        <div id="sidebar">
            SIDEBAR
        </div>
        <div id="content">
            CONTENT
        </div>
        <div id="footer">
            FOOTER
        </div>
    </div>
</body>
</html>
