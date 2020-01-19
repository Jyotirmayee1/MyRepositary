# MyRepositary
static boolean isNumber(String s) {
	for(int i=1;i<s.length();i++)
		if  (Character.isDigit(s.charAt(i))==false)
			return false;
	        return true;
}
	public static void main(String[] args) {
		// TODO Auto-generated method stub
		String str="Hii";
		if(isNumber(str)) {
			System.out.println( str+ "-->The given input is a integer");}
		else {
			System.out.println( str+ "-->The given input is a String");
			} }
}  
