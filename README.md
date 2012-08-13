Trivial - A Simple And Fast Web Toolkit
=======

Trivial是一个简单而快速(开发速度快、运行速度快)的Web开发工具箱。它基于Spring。

Trivial特别适合构建单机的中小型站点。

Trivial主要包含

<table>
    <tbody>
	    <tr>
		    <th>名称</th>
			<th>说明</th>
		</tr>
		<tr>
		    <td>DAO(Data Access Object)</td>
			<td>基于SpringJDBC的良好封装。此外提供了一个基于Ehcache的缓存DAO的实现。</td>
		</tr>
		<tr>
		    <td>Search</td>
			<td>基于Lucene的检索实现。简单、易扩展。同时，提供了对实时(Realtime)检索的支持。</td>
		</tr>
		<tr>
		    <td>Secure</td>
			<td>基于Spring AOP的简单权限管理。全注解。暂时没有提供对View层的支持。</td>
		</tr>
		<tr>
		    <td>Web</td>
			<td>对Servlet的封装，提供了请求上下文、非forward信息传递、缓存控制等功能。同时，还提供了Velocity页面片段缓存的指令。</td>
		</tr>
    </tbody>
</table>

Trivial已经应用于生产环境，并非学生课程作业般的玩具（尽管我也是学生）。
