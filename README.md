# BaseJava<br />
用户权限管理系统<br />
jdk:1.7<br />
登录账号:limingxing<br />
密码:123456<br />
以maven项目导入,导入完成后,右击pom.xml文件,选择run as——&gt;maven install(jar包会自动下载)<br />
导入baseweb数据库(mysql)<br/>
tomcat部署运行就好

有个依赖失效了，需要加个依赖
		<dependency>
			<groupId>net.sf.json-lib</groupId>
			<artifactId>json-lib</artifactId>
			<version>2.4</version>
			<classifier>jdk15</classifier>
		</dependency>
