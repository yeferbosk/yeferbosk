<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:0a0e1a,50:0a1a3a,100:0a0e1a&height=220&section=header&text=Yeferson%20Acosta&fontSize=52&fontColor=3b82f6&fontAlignY=38&desc=Backend%20Developer%20%7C%20Freelancer&descAlignY=60&descSize=18&descColor=60a5fa&animation=fadeIn"/>
  <source media="(prefers-color-scheme: light)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:e0ecff,50:bfdbfe,100:e0ecff&height=220&section=header&text=Yeferson%20Acosta&fontSize=52&fontColor=1d4ed8&fontAlignY=38&desc=Backend%20Developer%20%7C%20Freelancer&descAlignY=60&descSize=18&descColor=2563eb&animation=fadeIn"/>
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0e1a,50:0a1a3a,100:0a0e1a&height=220&section=header&text=Yeferson%20Acosta&fontSize=52&fontColor=3b82f6&fontAlignY=38&desc=Backend%20Developer%20%7C%20Freelancer&descAlignY=60&descSize=18&descColor=60a5fa&animation=fadeIn"/>
</picture>

<p>
<img src="https://img.shields.io/badge/Backend-Developer-2563eb?style=flat-square&labelColor=1e3a8a"/>
<img src="https://img.shields.io/badge/Freelancer-Disponible-3b82f6?style=flat-square&labelColor=1e3a8a"/>
<img src="https://img.shields.io/badge/Experiencia-3%2B%20años-60a5fa?style=flat-square&labelColor=1e3a8a&color=2563eb"/>
</p>

</div>

---

# 👨🏻‍💻 Sobre mí

```go
package main

import "fmt"

type Developer struct {
    Name       string
    Role       string
    Experience string
    Skills     []string
    Status     string
}

func main() {

    me := Developer{
        Name: "Yeferson Acosta",

        Role: "Backend Developer",

        Experience: "3+ años",

        Skills: []string{
            "Spring Boot",
            "Go",
            "Python",
            "Angular",
            "Docker",
            "SQL",
        },

        Status: "Disponible para nuevos proyectos 🚀",
    }

    fmt.Println("Hola, soy", me.Name)
}
