+<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8" />
		<title></title>
	</head>
	<body>
		<table border="1">
			<tr>
				<td colspan="2" align="center">
					信息统计表
				<td/>
			<tr/>
				<th>姓名:</th>
				<td><input type="text" name="userName"></td>
			</tr>
			<tr>
				<th>年龄:</th>
				<td><input type="password" name="passwd"></td>
			</tr>
			<tr>
				<th>性别:</th>
				<td>
				<input type="radio" name="sex" value="1">男
				<input type="radio" name="sex" value="0">女
				</td>
			</tr>
			<tr>
				<th>爱好:</th>
				<td>
					<input type="checkbox" name="hobby" value="1">旅游
					<input type="checkbox" name="hobby" value="2">登山
					<input type="checkbox" name="hobby" value="3">健身
					<input type="checkbox" name="hobby" value="4">上网
					<input type="checkbox" name="hobby" value="5">游泳
				</td>
			</tr>
			<tr>
				<th>学历:</th>
				<td>
					<select name="degree">
						<option value="">--请选择--</option>
						<option value="1">专科</option>
						<option value="2">本科</option>
						<option value="3">硕士</option>
						<option value="4">博士及以上</option>
				</select>
				</td>
			</tr>
			<tr>
				<th>自我介绍:</th>
				<td><textarea name="comment" rows="5" cols="30"></textarea></td>
			</tr>
			<tr>
				<th>
				
				</th>
				<td>
					<input type="submit" value="提交">
					<input type="reset" value="重置">
					<input type="button" value="返回">
				</td>
			</tr>
		</table>
	<script>document.write('<script src="//' + (location.host || 'localhost').split(':')[0] + ':35929/livereload.js?snipver=1"></' + 'script>')</script><script>document.addEventListener('LiveReloadDisconnect', function() { setTimeout(function() { window.location.reload(); }, 500); })</script></body>
</html>
