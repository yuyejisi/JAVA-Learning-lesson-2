/*
	定义Java中的变量
	定义出所有数据类型的变量
	四类八种
*/
public class Variable {
	public static void main(String[] args){
		//定义整数类型，字节类型，byte类型
		//内存中1个字节， -128 127
		byte b = 100;
		System.out.println(b);
		
		//定义整数类型，短整型，short类型
		//内存中2个字节， -32768 32767
		short s = 200;
		System.out.println(s);
		
		//定义整数类型，整型，int类型,赋值以最后一次为准
		//内存中4个字节， -2147483648 2147483647
		int i =5000001;
		i = 15;
		System.out.println(i);
		
		//定义整数类型，长整型，long类型
		//内存中8个字节
		long l = 100000000000000001L;
		System.out.println(l);
		
		//定义浮点数据，单精度 float类型，默认是double类型
		//内存中4个字节
		float f = 1.0F;
		System.out.println(f);
		
		//定义浮点数据，双精度 double类型
		//内存中8个字节
		double d = 2.2;
		System.out.println(d);
		
		//定义字符类型，char
		//内存中2个字节，必须单引号包裹，只能写1个字符
		char c = '龙';
		System.out.println(c);
		
		//定义布尔类型，boolean
		//内存中1个字节，数据值，true false
		boolean bool = true;
		System.out.println(bool);
	}
}
