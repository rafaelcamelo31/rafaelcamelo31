<p align="center">
    <img src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExZnB3bGhoMDZhc2Y2bWRwYjVqOHA2aDFsbzFxMW40cWF4ZXZlNGZmeiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/Nx0rz3jtxtEre/giphy.gif" />
</p>
<p align="center">
    <img src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExMzY1anNndXU3aGhyN20wYWFzcjRhM2x5Mm50bnFyOXVrZGFuYnhiYSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/8JTFsZmnTR1Rs1JFVP/giphy.gif"/>   
</p>

```golang
package main

import "fmt"

type Me struct {
    Name             string
    Codes            []string
    Frameworks       []string
    Infrastructures  []string
    Architectures    []string
    Interests        []string
    Languages        []string
}

func main() {
  about := &Me{
    Name: "Rafael Camelo",
    Codes: []string{"golang", "typescript", "node.js"},
    Frameworks: []string{"nestjs", "react", "gRPC"},
    Infrastructures: []string{"aws", "docker", "kubernetes"},
    Architectures: []string{"microservices", "three-tier architecture"},
    Interests: []string{"clean code and architecture", "system design"},
    Languages: []string{"🇯🇵", "🇧🇷", "🇺🇸"}
  }

  fmt.Println(about)
}
```
