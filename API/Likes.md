# 点赞API
请求方式：GET
必选参数：
<table>
  <tr>
    <td>参数</td>
    <td>类型</td>
    <td>说明</td>
  </tr>
  <tr>
    <td>user</td>
    <td>int or string</tr>
    <td>用户id，<br>如当前已登录用户的id</td>
  </tr>
  <tr>
    <td>post</td>
    <td>int or string</tr>
    <td>文章id，如当前文章的id</td>
  </tr>
  <tr>
    <td>echo</td>
    <td>int or string or bool</tr>
    <td>true或false。true时，将数据推入数据库；<br>false时，仅输出已经点赞的用户</td>
  </tr>
</table>
