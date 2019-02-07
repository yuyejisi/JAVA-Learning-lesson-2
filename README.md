/*
	数据类型转换
	自动：取值范围小的类型，自动转换成取值范围大的类型
	一个类型boolean不参与类型转换
*/
public class DataConvert{
	public static void main(String[] args){
		//定义double类型的变量
		double d = 1000;//出现类型的自动转换，int自动转成double
		System.out.println(d);
		
		int i=100;
		double d2 = i;//出现类型的自动转换，int自动转成double
		System.out.println(d2);
		
		byte b = 10;
		int j = b; //自动类型转换,byte自动转换成int
		System.out.println(j);
	}
}
