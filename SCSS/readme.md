1、sass嵌套输出方式nested
sass index.scss:index.css --style nested
sass --watch index.scss:index.css --style nested (加了实时监控)

2、sass展开输出方式expanded
sass index.scss:index.css --style expanded

3、sass展开输出方式compact
sass index.scss:index.css --style compact

4、sass展开输出方式compressed
sass index.scss:index.css --style compressed

5、sass变量声明
$+变量名+：+变量值；
eg: $width: 200px;