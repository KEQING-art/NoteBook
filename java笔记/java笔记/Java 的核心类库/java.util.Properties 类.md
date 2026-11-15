Properties 类的作用
它 是Java 里专门用来读写 .properties 配置文件的工具类。

Properties 类的load 方法
Properties 实例.load( 类加载器的getResourceAsStream方法选中的properties文件，返回的inputStream实例);
这个方法可以让Properties实例, 能够读取对应Properties配置文件文件.
注意：这个方法默认用ISO-8859-1 编码。

Properties 类的getProperty 方法
Properties 实例.getProperty( "键名");
这个方法可以读取Properties 实例的Properties 配置文件对应键名的值, 以字符串的形式返回。

