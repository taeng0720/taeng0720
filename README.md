
```cs
using UnityEngine;

public class Taeng : Taeng_Github
{
    public string Name = "Kim Tae Woo";
    public readonly Birthday = "2007_07_20";
    [SerializeField]
    private string Learning;
    public string[] Awards_array = new string[3];
    void FixedUpdate()
    {
        Study();
        Awards();
    }
    void Study()
    {
        public String Spring = "Low";
        public String React = "Low";
        public String Java = "Middle";
        public String Csharp = "Middle";
        public String Unity = "High";
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
        /*
        if(Learning == "Planning")
        {
            Awards_array[4] = ""; 
            Awards_array[5] = ""; 
            Awards_array[6] = "";
            Awards_array[7] = ""; 
        }
        if(Learning == "Web")
        {
            Awards_array[8] = ""; 
            Awards_array[9] = ""; 
            Awards_array[10] = "";
            Awards_array[11] = ""; 
        }
*/
    }

}
```
