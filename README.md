# Starter_Go
Beginner's guide to Golang with essential concepts and a simple CLI task manager project to practice required skills.

# Golang Beginner Guide

Welcome to your Go (Golang) journey! Let's introduce basic Golang concepts

---

## 🧠 Basic Concepts of Go

### 1. **Hello, World**
```go
package main
import "fmt"

func main() {
    fmt.Println("Hello, World!")
}
```
- `package main`: Defines an executable program
- `import`: Brings in packages (like libraries)
- `func main()`: Entry point of the program

### 2. **Variables**
```go
var name string = "Gopher"
age := 10 // shorthand
```
- Static typing with type inference

### 3. **Functions**
```go
func add(a int, b int) int {
    return a + b
}
```
- Functions can return multiple values

### 4. **Control Flow**
```go
if age > 18 {
    fmt.Println("Adult")
} else {
    fmt.Println("Minor")
}
```

### 5. **Loops**
```go
for i := 0; i < 5; i++ {
    fmt.Println(i)
}
```
- Go only has `for` loop (no `while`)

### 6. **Arrays and Slices**
```go
arr := [3]int{1, 2, 3}
slice := []int{1, 2, 3, 4}
```

### 7. **Maps**
```go
m := map[string]int{"apple": 5, "banana": 3}
```

### 8. **Structs**
```go
type Person struct {
    Name string
    Age  int
}
```

### 9. **Pointers**
```go
var x int = 10
p := &x
fmt.Println(*p) // prints 10
```

### 10. **Concurrency with Goroutines**
```go
func say(msg string) {
    fmt.Println(msg)
}

go say("Hello") // runs concurrently
```

---

## 🚀 Starter Project: CLI Task Manager

### Project Idea:
Build a simple command-line task manager where you can:
- Add a task
- List tasks
- Mark a task as done
- Delete a task

### Key Concepts You’ll Learn:
- File I/O (for saving tasks)
- Structs and slices
- Command-line arguments using `flag` package
- Error handling

### GitHub Starter Repository:
You can fork and clone this starter template:
🔗 [https://github.com/adeven/go-task-manager](https://github.com/adeven/go-task-manager) *(or search: go-task-manager on GitHub)*

### To Run:
```bash
go run main.go add "Learn Go"
go run main.go list
```

### Stretch Goals:
- Save tasks to a JSON file
- Add timestamps
- Sort tasks
- Add search functionality

---

## ✅ Next Steps
- [ ] Install Go from https://golang.org/dl/
- [ ] Setup VS Code with Go plugin
- [ ] Clone the project above
- [ ] Read & edit the code
- [ ] Try building your own version!

Happy Coding! 🧑‍💻

---

> Maintained by your Go learning companion. Fork, Learn, Modify!
