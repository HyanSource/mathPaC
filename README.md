# mathPaC
排列組合公式包

## F (factorial)
- 階層公式
```go
func main() {
    //9!
    t := mathPaC.F(9)
    fmt.Println(t)
}
```
## P (permutations)
- 排列公式
```go
func main() {
    //P82
    t := mathPaC.P(8,2)
    fmt.Println(t)
}
```
## C (combination)
- 組合公式
```go
func main() {
    //C54
    t := mathPaC.C(5,4)
    fmt.Println(t)
}
```
## H (combination with repetition)
- 重複組合公式
```go
func main() {
    //H24
    t := mathPaC.H(2,4)
    fmt.Println(t)
}
```