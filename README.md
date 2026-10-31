# 📝 To-Do List Console App

A simple command-line to-do list built in C# to practice core fundamentals: `List<T>`, loops, conditionals, and user input.

## Features
- Add a task
- Remove a task by number
- View all tasks
- Menu runs until you enter `e` to exit
- Shows a message for invalid menu options

## Tech Stack
C# | .NET | Console Application

## Project Structure
```
Todo-List-Program/
├── ConsoleApp1/      # C# console project (Program.cs)
└── README.md
```

## Getting Started

### Prerequisites
- [.NET SDK](https://dotnet.microsoft.com/download) or Visual Studio

### Run from the command line
```bash
git clone https://github.com/NadimMolla1010/Todo-List-Program.git
cd Todo-List-Program/ConsoleApp1
dotnet run
```

### Run from Visual Studio
Open the project in the `ConsoleApp1` folder and press `F5`.

## Usage

| Input | Action |
|-------|--------|
| `1` | Add a task |
| `2` | Remove a task (enter its number) |
| `3` | View the list |
| `e` | Exit |

## What I Practiced
- Storing data with `List<string>` (`Add`, `RemoveAt`, `Count`)
- Program flow with a `while` loop and `if / else if / else`
- Reading and converting console input

## Limitations
- Tasks are stored in memory only, so they are lost when the program closes.
- Entering a non-numeric or out-of-range number when removing a task is not handled yet.

## Planned Improvements
- [ ] Validate input with `int.TryParse`
- [ ] Save tasks to a file
- [ ] Refactor into `TaskItem` and `TaskManager` classes

## Author
**Md Nadim Molla** | [LinkedIn](https://linkedin.com/in/nadim-molla) | [GitHub](https://github.com/NadimMolla1010)
