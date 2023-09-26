# Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.
A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues. 


- In order to create codeblocks in markdown you need to use three backticks (`)
- Not to be confused with single quotation (')
```
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

puts "Enter a number to calculate its factorial:"
number = gets.chomp.to_i

if number < 0
  puts "Factorial is not defined for negative numbers."
else
  result = factorial(number)
  puts "The factorial of #{number} is #{result}."
end
```

- When you can you should attempt to apply syntax highlighting to your codeblocks
```ruby
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

puts "Enter a number to calculate its factorial:"
number = gets.chomp.to_i

if number < 0
  puts "Factorial is not defined for negative numbers."
else
  result = factorial(number)
  puts "The factorial of #{number} is #{result}."
end
```

- Make note of where the backtick button is located.
- It should appear next to the letter 'z' key on your Macbook Pro.

<img width=500px src="https://github.com/samboateng23/github-docs-example/assets/126742866/18c25edc-0898-4af4-8212-16198603e130" />

Good Cloud Engineers use codeblocks for both Code and Errors that appear in the console. 

```bash
NameError: undefined local variable or method `undefined_variable' for main:Object
```

> Here is an example of using a codeblock for an error that appears in bash.

## Step 3 - Use Github Flavoured Markdown Task Lists

Github extends Markdown to have a list where you can check off items.

- [x] Finish Step 1
- [ ] Finish Step 2
- [ ] Finish Step 3 

## References
- [Basic Writing and Formatting Syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#links)
- [Github Flavoured Markdown Spec](https://github.github.com/gfm/)
- [GFM - Tasks Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists)
