```cs
using UnityEngine;

public class Taeng_README : Taeng_Github
{
    public string Name = "Kim Tae Woo";
    public readonly Birthday = "2007_07_20";
    public string Learning = "Unity";
    public string[] Awards_array = new string[3];
    void Update()
    {
    }
    void Awards()
    {
        if(Learning == "Unity")
        {
            Awards_array[0] = "STAC"; 
            Awards_array[1] = "AppJam_24"; 
            Awards_array[2] = "Rookie_Challengers";
            Awards_array[3] = "AppJam_25"; 
        }
    }
}
```
