```cs
using UnityEngine;

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
    private string Learning; // 현재 배우고 있는 기술

    // 🏆 수상 목록 (기본 크기 설정)
    public string[] Awards_array = new string[4];

    // 🎮 Unity FixedUpdate (매 프레임마다 실행됨)
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
            { "Csharp", "Middle" },
            { "Unity", "High" }
        };

        // 📝 학습 내용 출력
        foreach (var skill in skills)
        {
            Debug.Log($"🔹 {skill.Key}: {skill.Value}");
        }
    }

    // 🏅 수상 내역 업데이트
    void Awards()
    {
        if (Learning == "Unity")
        {
            Awards_array[0] = "🏆 STAC"; 
            Awards_array[1] = "🎨 AppJam_24"; 
            Awards_array[2] = "🚀 Rookie_Challengers";
            Awards_array[3] = "🔥 AppJam_25"; 
        }

        // 📝 수상 내역 출력
        foreach (var award in Awards_array)
        {
            Debug.Log($"🏅 {award}");
        }
    }
}

// --------------------------------
// 🎨 Keep Growing, Keep Coding 🚀
// --------------------------------
```
