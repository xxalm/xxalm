
<div style="text-align: right; margin-top: 50px; margin-right: 50px;">
  <img src="avatar2.gif" width="400" />
</div>

###

```csh
using System;

public class Developer {
  public string Name { get; set; }
  public string Field { get; set; }
  public string Company { get; set; }
  public string Location { get; set; }
  public Skills DeveloperSkills { get; set; }

  public Developer(string name, string field, string company, string location, Skills developerSkills) {
    Name = name;
    Field = field;
    Company = company;
    Location = location;
    DeveloperSkills = developerSkills;
  }
}

public class AboutMe : Developer {
  public AboutMe() 
      : base("Leckson", ".NET/C# Developer", "Outlier", "Brazil", new Skills()) {
  }
}

public class Skills {
  public string[] Languages { get; set; }
  public string[] Libraries { get; set; }
  public string[] Frameworks { get; set; }

  public Skills() {
    Languages = new string[] { "C#", "JavaScript", "Java", "Ruby", "Python", "PHP" };
    Libraries = new string[] { "React" };
    Frameworks = new string[] { ".NET", "Angular", "Vue.js", "Node.js", "Ruby on Rails", "Laravel" };
  }
}

```

### ⚙️ GitHub Analytics

<table>
  <tr>
    <td>
      <img
        align="left"
        width="400"
        src="https://github-readme-stats.vercel.app/api?username=xxalm&theme=dark&hide_border=false&include_all_commits=true"
        alt="Github Stats"
      />
    </td>
    <td>
      <img
        align="left"
        width="350"
        src="https://github-readme-stats.vercel.app/api/top-langs/?username=xxalm&theme=dark&hide_border=false&include_all_commits=true&count_private=true&layout=compact"
        alt="Github Stats"
      />
    </td>
    <td>
      <br />
      <img
        align="left"
        width="350"
        src="https://github-readme-streak-stats.herokuapp.com/?user=xxalm&theme=dark&hide_border=false"
        alt="Github Stats"
      />
    </td>
  </tr>
</table>

--- 

### 🏆 GitHub Profile Trophy

<p align="center">
  <a
    href="https://github.com/ryo-ma/github-profile-trophy"
    title="repositório de troféus"
  >
    <img
      width="800"
      src="https://github-profile-trophy.vercel.app/?username=xxalm&column=8&theme=darkhub&no-frame=true&no-bg=true"
    />
  </a>
</p>

---

