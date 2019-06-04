# GolangSamplePackageStructure
Learning the package structure of Go

Saving this example for myself to reference. The package structure of a Go project:

- Workspace   (call this whatever, this is your $GOPATH)
  - bin    (your $GOBIN)
     - binaries
  - src
     - github.com
      - <USERNAME>
        - project1
          -mainFolder
            - main.go
          - moduleFolder
            - someModule.go
  - pkg
      - packages from "go install" (you can import these, they're compiled)
