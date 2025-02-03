```cs
using UnityEngine;
using System.Collections.Generic;

// 🎨 Taeng's GitHub Profile Code 🏆
// --------------------------------
// 🖥️ Game Developer | 🎮 Unity Enthusiast | 🚀 Always Learning
// --------------------------------

public class Taeng : Taeng_Github
{
    // 👤 Personal Information
    public string Name = "Kim Tae Woo";
    public readonly string Birthday = "2007_07_20";

    [SerializeField]
    private string Learning;

    public List<string> Awards_list = new List<string>();

    public List<string> Collaborations = new List<string>();

    void FixedUpdate()
    {
        Study();   // 📖 학습 중인 기술 업데이트
        Awards();  // 🏆 수상 내역 업데이트
    }

    // 📚 학습 중인 기술 리스트
    void Study()
    {
        var skills = new Dictionary<string, string>
        {
            { "Spring", "Low" },
            { "React", "Low" },
            { "Java", "Middle" },
            { "Photo Shop", "Middle" },
            { "Csharp", "Middle" },
            { "Unity", "High" }
        };
    }

    // 🏅 수상 내역 업데이트
    void Awards()
    {
        Awards_list.Add("🏴‍☠️ LogCon Hackathon Winner (Cybersecurity & Hacking)");
        Awards_list.Add("📌 Gyeongbuk Creative Convergence Talent Development Project (Planning)");
        Awards_list.Add("🤖 SW-AI Talent Development Project - Finalist (Planning)");
        Awards_list.Add("🏆 STAC");
        Awards_list.Add("🎨 AppJam_24");
        Awards_list.Add("🚀 Rookie_Challengers");
        Awards_list.Add("🔥 AppJam_25");

    }
    void Collaborate()
    {
        Collaborations.Add("🚀 Mainoo Games (Ongoing)");
        Collaborations.Add("🎮 용 게임즈 (Ongoing)");
        Collaborations.Add("🐰 Rabbit Hole (Completed)");
    }
}

// --------------------------------
// 🎨 Keep Growing, Keep Coding 🚀
// --------------------------------
```
