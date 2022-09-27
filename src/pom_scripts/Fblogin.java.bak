package pom_scripts;

import org.openqa.selenium.WebDriver;
import org.openqa.selenium.WebElement;
import org.openqa.selenium.support.FindBy;
import org.openqa.selenium.support.PageFactory;

public class Fblogin {
	@FindBy(xpath="//input[@id='email']")
	private WebElement email;
	@FindBy(xpath="//input[@id='pass']")
	private WebElement pwd;
	@FindBy(xpath="//button[.='Log In']")
	private WebElement loginbtn;
	
	public Fblogin(WebDriver driver)
	{
		PageFactory.initElements(driver,this);
	}
	
	public void setEmail(String em)
	{
		email.sendKeys(em);
	}
	public void setpwd(String pd)
	{
		pwd.sendKeys(pd);
	}
	public void ln()
	{
		loginbtn.click();
	}

}
