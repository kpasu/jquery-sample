# jquery-sample

```
<html>
    <head>
        <script src="http://code.jquery.com/jquery.min.js"></script>
    </head>
    <body>
        <input type="button" id="test1" value="wrap"><br><br>
        <input type="button" id="test2" value="unwrap"><br><br>
        <select>
            <option data-hoge='1'>1000</option>
            <option data-hoge='2'>2000</option>
            <option data-hoge='3'>3000</option>
            <option data-hoge='4'>4000</option>
        </select>

        <script>
                $("#test1").click(function() {
                    $('[data-hoge="2"]').wrap('<span style="display: none;">');
                });
                $("#test2").click(function() {
                    $('[data-hoge="2"]').unwrap();
                });
        </script>
    </body>
</html>
```
