<p style="coler="red">`Language`</p>

<p>
使用keytool命令生成证书：<br>
keytool <br>
-genkey <br>
-alias tomcat(别名) <br>
-keypass 123456(别名密码) <br>
-keyalg RSA(算法) <br>
-keysize 1024(密钥长度) <br>
-validity 365(有效期，天单位) <br>
-keystore D:/keys/tomcat.keystore(指定生成证书的位置和证书名称) <br>
-storepass 123456(获取keystore信息的密码)<br>

keytool -genkey -alias tomcat -keypass 123456 -keyalg RSA -keysize 1024 -validity 365 -keystore D:/keys/tomcat.keystore -storepass 123456
</p>