/*
	三元运算符
	公式：
		布尔表达式 ? 结果1:结果2;
		布尔表达式结果是true,三元运算符的结果,就是  结果1
		布尔表达式结果是false,三元运算符的结果,就是 结果2
*/
public class Operator_5{
	public static void main(String[] args){
		System.out.println(3>2?99:98);
		System.out.println(3>5?99:98);
		
		String s = 0==0?"哈哈":"呵呵";
		System.out.println(s);
	}
}
