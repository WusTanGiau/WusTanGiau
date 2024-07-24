```golang
package main

import (
    "wustangiau"
    "github.com/WusTanGiau"
)

type Github struct {
    username string
    contacts map[string]string
    alises   []string
    location string
    age      string
    occupation string
    operating_system string
}

func (g *Github) Init() {
    g.username = "TanGiau"
    g.contacts = map[string]string{
        "Discord": "WusTanGiau",
        "Facebook": "wustangiau",
    }
    g.alises = []string{"TanGiauDev", "TGV"}
    g.location = "localhost, vietnamese"
    g.age = "24+"
    g.occupation = "Freelance Developer"
    g.operating_system = "Windows, Arch, Linux, VPS"
}
```
