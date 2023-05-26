```csharp
public class SoftwareEngineer
{
    public string Name { get; }
    public AboutMe AboutMe { get; }
    public IEnumerable<Languages> Languages { get; }
    public FunFact FunFact { get; }

    public SoftwareEngineer(string name, AboutMe aboutMe, IEnumerable<Languages> languages, FunFact funFact)
    {
        Name = name;
        AboutMe = aboutMe;
        Languages = languages;
        FunFact = funFact;
    }
}

var ricardo = new SoftwareEngineer(
    name: "Ricardo Tondello",
    aboutMe: new AboutMe("I'm currently working at https://www.nmbrs.com as a Software Engineer. 
                          Brazilian, Italian Citizen and living in Amsterdam"),
    languages: new[] { "Portuguese", "English", "Italian" }, 
    funFact: new FunFact("I don't have the right arm"));
```

![](https://komarev.com/ghpvc/?username=ricardotondello)

## 🏆 GitHub Trophies

[![trophy](https://github-profile-trophy.vercel.app/?username=ricardotondello&theme=nord&column=7)](https://github.com/ryo-ma/github-profile-trophy)

![Snake animation](https://github.com/ricardotondello/ricardotondello/blob/main/github-contribution-grid-snake.svg)
