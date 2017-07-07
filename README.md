# automate-world
my first automation 


package koundinya;

import org.openqa.selenium.chrome.ChromeDriver;

public class Krish01 {

	
	public static void main(String[] args) {
		System.setProperty("webdriver.chrome.driver","D:\\nkrishnakoundinya\\chromedriver.exe");
		ChromeDriver driver=new ChromeDriver();
		driver.get("https://www.quora.com");
		
	}

}
