# NovaLang

NovaLang is a small, simple programming language built in C++ with its own compiler and virtual machine.

The goal is to keep things easy to understand, hackable, and fun to experiment with.

---

## ✨ What it can do

* Clean, simple syntax, a mix between C# and Python
* Functions, structs, variables
* Control flow: `if`, `while`, `for`, `for in`
* Lists with basic operations
* Imports (including a small stdlib)
* Runs through a custom VM (fast enough for experimentation)

---

## 📦 Example

```cs
func main() {
    list nums = [1, 2, 3]
    nums.push(4)
    println(len(nums))
}
```

---

## 🚀 Getting Started

### Build

You can build the project with the README_BUILD.md instructions in the Novalang repository.

### Run

```bash
./nova your_file.nv
```

---

## 📁 Project Structure (simple)

```
novalang/
├── src/        # all core code (compiler + VM + shell)
├── include/    # all header files (like vm.h)
├── standardlib/     # standard library files
└── src/main.cpp    # entry point
```

---

## 📌 Roadmap

* [ ] Better error messages
* [ ] Improve type system
* [ ] Expand standard library
* [ ] Better imports / modules
* [ ] Performance improvements
* [ ] Better memory management

---

## 🤝 Contributing

PRs are welcome.

Guidelines:

* Keep code simple and readable
* Don’t over-comment — explain *why*, not every line
* Stay consistent with existing style

---

## 📜 License

MIT

---

## 💡 Why this exists

NovaLang is mainly for:

* Learning how languages work
* Experimenting with ideas
* Building something cool without overengineering 

---

## ⭐ Support

If you like it, give it a star.
