# cake

* https://cakebuild.net/
* tutorials
  * [Cake + .NET Core = Write Once, Build Anywhere](https://www.youtube.com/watch?v=FKbykwvB_MU)
  * [Intro to Cake: Cross Platform Build Automation in C#](https://www.youtube.com/watch?time_continue=9&v=WbaR2-v6JXQ)
  * [A Piece of Cake - C# powered cross platform build automation](https://www.youtube.com/watch?v=zZIyEn4jF2U)
  + [cake course pluralsight](https://www.pluralsight.com/courses/cake-applications-deploying-building)


```csharp
public class TVO : MvvmObject {
	public TVO(ScanCodeType type, string code)
	{
		Type.Value = type;
		Code.Value = code;
	}
	    public MvvmProperty<ScanCodeType> Type { get; set; } = new MvvmProperty<ScanCodeType>();
	    public MvvmProperty<string> Code { get; set; } = new MvvmProperty<string>();
	}
 ```
