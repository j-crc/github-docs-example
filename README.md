# Writing good documentation

## Step 1 - Using codeblocks
Codeblocks in markdown make it very easy for tech people to *copy, paste, and share code* because it allows otehr to copy and paste their code to replicate or research issues.

- A good Cloud Engineer uses codeblocks whenever possible. When you can, you should attempt to apply syntax highlighting to your codeblocks, like this:

```ruby
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

# Calculate the factorial of 5
result = factorial(5)
puts "Factorial of 5 is #{result}"
```


- Make note of where the backtick button is located on your keyboard (it varies depending on your kb layout/region).

<img src="https://github.com/j-crc/github-docs-example/assets/107445418/c5bee169-5064-4236-9e60-e142ca2b4303" alt="dog meme" width="200"> 

- Good Cloud Engineers use codeblocks for both code and code errors that appear on the console. Here is an example of using codeblocks for an error that appears in bash.


```bash
$ nonExistentCommand
bash: nonExistentCommand: command not found
```


This is a random quote:

> _"I am Beyoncé always"_ Michael Scott



## Step 2 - How to take screenshots

A screenshot is when you capture a part of your screen from your laptop, desktop or phone. This is not to be confused with taking a photo with your phone.

_Immediately no_ :raised_back_of_hand:

<img src="/assets/programming-horror.jpg" alt="photo of computer taken with phone" width="300">


I suggest using Lighshot [<sup>[1]</sup>](#references), it works on Windows and Mac. With this tool, you can capture the screen or part of it and save it as an image or paste it on Paint.



## Step 3 - Using Github Flavored Task lists

Github extends markdown to have a list where you can check off items.[<sup>[2]</sup>](#references)

- [x] Finish Step 1
- [ ] Finish Step 2
- [x] Finish Step 3
- [x] Create more steps :tada:


## Step 4 - Using Emojis

Github Flavored Markdown supports emoji shortcodes. Here are some examples:

| Name       | Shortcode   | Emoji |
|------------|------------ |-------|
| Smile      |   `:smile:`   |  😊   |
| Heart      |   `:heart:`   |  ❤️   |
| Thumbs Up  |   `:+1:`      |  👍  |
| Coffee     |   `:coffee:`  |  ☕  |
| Cloud     |   `:cloud:`  |  ☁️  |



## References

- [Github Flavored Markdown Spec](https://github.github.com/gfm/)

- [Github Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

- [Lightshot screen capture tool](https://app.prntscr.com/en/index.html)<sup>[1]</sup>
 
- [GFM Task lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) <sup>[2]</sup>

- [GFM Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)
  
