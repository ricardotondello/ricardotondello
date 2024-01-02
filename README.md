```csharp
public class SoftwareEngineer
{
    public string Name { get; }
    public AboutMe AboutMe { get; }
    public IEnumerable<Language> Languages { get; }
    public FunFact FunFact { get; }

    public SoftwareEngineer(string name, AboutMe aboutMe, IEnumerable<Language> languages, FunFact funFact)
    {
        Name = name;
        AboutMe = aboutMe;
        Languages = languages;
        FunFact = funFact;
    }
}

var ricardo = new SoftwareEngineer(
    name: "Ricardo Tondello",
    aboutMe: new AboutMe("I'm currently working at https://www.nmbrs.com as a Software Engineer in Amsterdam 🇳🇱"),
    languages: new[] { "Portuguese 🇧🇷", "English 🇬🇧", "Italian 🤌" }, 
    funFact: throw new BodyException("Right arm not found!"));
```

<a href="https://www.buymeacoffee.com/ricardotondello" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>

## 🏆 GitHub Trophies

[![trophy](https://github-profile-trophy.vercel.app/?username=ricardotondello&theme=nord&column=7)](https://github.com/ryo-ma/github-profile-trophy)

![Snake animation](https://github.com/ricardotondello/ricardotondello/blob/main/github-contribution-grid-snake.svg)
