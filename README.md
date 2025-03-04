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
###
