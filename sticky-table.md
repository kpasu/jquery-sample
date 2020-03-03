# sticky-table

```
<html>
    <head>
        <style>

.content {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translateY(-50%) translateX(-50%);
}

.sticky_table_wrapper {
    overflow-y: scroll;
    height: 40vh;
}

.sticky_table thead th {
    position: -webkit-sticky;
    position: sticky;
    top: 0;
    z-index: 1;
    background-color: #ffffff;
}

th {
    padding: 1px 5px;
}

.disp {
    position: absolute;
    top: -9999px;
}

        </style>
    </head>

    <body>
        <div class="content">
            <div class="sticky_table_wrapper">
                <table class="sticky_table">
                    <thead>
                        <tr>
                            <th class="hoge1">head</th>
                            <th class="hoge1">head</th>
                            <th class="hoge1">head</th>
                            <th>head</th>
                            <th>head</th>
                            <th>head</th>
                            <th>head</th>
                            <th>head</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>data1</td>
                            <td>data1</td>
                            <td>data1</td>
                            <td>data1</td>
                            <td>data1</td>
                            <td>data1</td>
                            <td>data1</td>
                            <td>data1</td>
                        </tr>
                        <tr>
                            <td>data2</td>
                            <td>data2</td>
                            <td>data2</td>
                            <td>data2</td>
                            <td>data2</td>
                            <td>data2</td>
                            <td>data2</td>
                            <td>data2</td>
                        </tr>
                        <tr>
                            <td>data3</td>
                            <td>data3</td>
                            <td>data3</td>
                            <td>data3</td>
                            <td>data3</td>
                            <td>data3</td>
                            <td>data3</td>
                            <td>data3</td>
                        </tr>
                        <tr>
                            <td>data4</td>
                            <td>data4</td>
                            <td>data4</td>
                            <td>data4</td>
                            <td>data4</td>
                            <td>data4</td>
                            <td>data4</td>
                            <td>data4</td>
                        </tr>
                        <tr>
                            <td>data5</td>
                            <td>data5</td>
                            <td>data5</td>
                            <td>data5</td>
                            <td>data5</td>
                            <td>data5</td>
                            <td>data5</td>
                            <td>data5</td>
                        </tr>
                        <tr>
                            <td>data6</td>
                            <td>data6</td>
                            <td>data6</td>
                            <td>data6</td>
                            <td>data6</td>
                            <td>data6</td>
                            <td>data6</td>
                            <td>data6</td>
                        </tr>
                        <tr>
                            <td>data7</td>
                            <td>data7</td>
                            <td>data7</td>
                            <td>data7</td>
                            <td>data7</td>
                            <td>data7</td>
                            <td>data7</td>
                            <td>data7</td>
                        </tr>
                        <tr>
                            <td>data8</td>
                            <td>data8</td>
                            <td>data8</td>
                            <td>data8</td>
                            <td>data8</td>
                            <td>data8</td>
                            <td>data8</td>
                            <td>data8</td>
                        </tr>
                        <tr>
                            <td>data9</td>
                            <td>data9</td>
                            <td>data9</td>
                            <td>data9</td>
                            <td>data9</td>
                            <td>data9</td>
                            <td>data9</td>
                            <td>data9</td>
                        </tr>
                        <tr>
                            <td>data0</td>
                            <td>data0</td>
                            <td>data0</td>
                            <td>data0</td>
                            <td>data0</td>
                            <td>data0</td>
                            <td>data0</td>
                            <td>data0</td>
                        </tr>
                        <tr>
                            <td>data1</td>
                            <td>data1</td>
                            <td>data1</td>
                            <td>data1</td>
                            <td>data1</td>
                            <td>data1</td>
                            <td>data1</td>
                            <td>data1</td>
                        </tr>
                        <tr>
                            <td>data2</td>
                            <td>data2</td>
                            <td>data2</td>
                            <td>data2</td>
                            <td>data2</td>
                            <td>data2</td>
                            <td>data2</td>
                            <td>data2</td>
                        </tr>
                        <tr>
                            <td>data3</td>
                            <td>data3</td>
                            <td>data3</td>
                            <td>data3</td>
                            <td>data3</td>
                            <td>data3</td>
                            <td>data3</td>
                            <td>data3</td>
                        </tr>
                        <tr>
                            <td>data4</td>
                            <td>data4</td>
                            <td>data4</td>
                            <td>data4</td>
                            <td>data4</td>
                            <td>data4</td>
                            <td>data4</td>
                            <td>data4</td>
                        </tr>
                        <tr>
                            <td>data5</td>
                            <td>data5</td>
                            <td>data5</td>
                            <td>data5</td>
                            <td>data5</td>
                            <td>data5</td>
                            <td>data5</td>
                            <td>data5</td>
                        </tr>
                        <tr>
                            <td>data6</td>
                            <td>data6</td>
                            <td>data6</td>
                            <td>data6</td>
                            <td>data6</td>
                            <td>data6</td>
                            <td>data6</td>
                            <td>data6</td>
                        </tr>
                        <tr>
                            <td>data7</td>
                            <td>data7</td>
                            <td>data7</td>
                            <td>data7</td>
                            <td>data7</td>
                            <td>data7</td>
                            <td>data7</td>
                            <td>data7</td>
                        </tr>
                        <tr>
                            <td>data8</td>
                            <td>data8</td>
                            <td>data8</td>
                            <td>data8</td>
                            <td>data8</td>
                            <td>data8</td>
                            <td>data8</td>
                            <td>data8</td>
                        </tr>
                        <tr>
                            <td>data9</td>
                            <td>data9</td>
                            <td>data9</td>
                            <td>data9</td>
                            <td>data9</td>
                            <td>data9</td>
                            <td>data9</td>
                            <td>data9</td>
                        </tr>
                        <tr>
                            <td>data0</td>
                            <td>data0</td>
                            <td>data0</td>
                            <td>data0</td>
                            <td>data0</td>
                            <td>data0</td>
                            <td>data0</td>
                            <td>data0</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </div>

        <div class="disp">
            <ul>
                <li>hogehoge1</li>
                <li>hogehoge2</li>
                <li>hogehoge3</li>
            </ul>
        </div>

        <script
            src="https://code.jquery.com/jquery-3.4.1.min.js"
            integrity="sha256-CSXorXvZcTkaix6Yvo6HppcZGetbYMGWSFlBw8HfCJo="
            crossorigin="anonymous">
        </script>
        <script>
$(function() {
    $(".hoge1").hover(
        function () {
            $(".disp")
                .css({
                    top: $(this).offset().top - $(".disp").height(),
                    left: $(this).offset().left,
                });
        },function () {
            $(".disp")
                .css({
                    top: -9999
                });
        }
    );
});
        </script>
    </body>
</html>
```
