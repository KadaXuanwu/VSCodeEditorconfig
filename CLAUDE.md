# C# Code Style

- Use **K&R bracing style**: opening brace on the same line, not on a new line.
- Indent with **4 spaces**, no tabs.
- Use **explicit types** — no `var`.
- Trim trailing whitespace. Always end files with a newline.
- Indent `switch` case labels.
- Do not indent braces themselves, only their contents.
- Use UTF-8 encoding.

```csharp
// Correct
public void DoSomething() {
    if (condition) {
        Execute();
    }
}

// Wrong
public void DoSomething()
{
    if (condition)
    {
        Execute();
    }
}
```
