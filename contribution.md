# Contribution

This book is under [CC BY-NC-SA License](https://creativecommons.org/licenses/by-nc-sa/3.0/) so we appreciate all kinds of contributions, distribution and we preserve our contributors efforts, forever.

Note: The code in this book is tested on Ruby version &gt; 2.2.0

## Contribution methods

There are several kinds of contributions that could help this book achieve the best results:

- Contribution by adding tricky code.
- Contribution by adding more explanation for existing code.
- Contribution by enhancing the code quality or alternatives.
- Contribution by enhancing the book quality:
  - Structure enhancements
  - Spelling, proofreading enhancements
  - Design enhancements
  - Ideas and requests
  - Any other
- Contribution by spreading the book in social media and IS communities.
  - Twitter: [@Rubyfu](https://twitter.com/Rubyfu) and hashtag `#Rubyfu`
  - Google+: [Rubyfu page](https://plus.google.com/114358908164154763697)
- Contribution by adding more resources and references.
- Contribution by donation.

## How to?

### Start contributing

Please find all you need to know about GitBook and markdown editing in the [References](references.md) section. As good start, you can refer to [how to use it from official readme](https://github.com/GitbookIO/gitbook). You can easily use GitBook [Desktop editor](https://app.gitbook.com/).

1. Create a [GitHub](https://github.com) account.
2. Fork [RubyFu repository](https://github.com/rubyfu/RubyFu).
3. Clone GitHub forked RubyFu repository:

   `git clone https://github.com/[YourGithubAccount]/RubyFu`

4. Create a [GitBook](http://gitbook.com) account.
5. Go to [**GitBook editor**](https://app.gitbook.com/) and Sign-in with your GitBook account
6. Press the **Import** button to import the cloned repository. Then, you'll find it in the **URL** tab.
7. Add the forked RubyFu repository GitHub URL to GitBook Editor in the URL tab : **Home** &gt;&gt; **Import** &gt;&gt; **URL**
   <br/>

![](import.gif)

8. Start your awesome contribution.
9. From GitBook editor, **Sync** your changes to the forked repository.
10. From GitHub, send a **Pull Request\(PR\)** to the **Master** branch.

Not sure where to start helping? Go to [TODO list](contributors/todo.md) and check the unchecked items.

### Contributing with Code

#### Ruby code

- Use the triple ticks `` followed by `ruby` then your code in between the`` to get ruby code highlighted. e.g.

  ```ruby
        puts "Ruby Code here"
  ```

- Explain the main idea -with some details- of the code, if you explain every line that would be great but it's not a must.
- Choose the correct Module.
- Make your title clear.
- Use Text editor/ide for code identification before pasting your code.
- Mention the source, if you copied or developed code that has been created by others; please mention the source in the footer. e.g.

  ```ruby
        puts "Your good code"
  ```

  ```text
    [Source][1]
  ```

  Then add the following to the footer

  ```text
    [1]: http://TheSouceCodeURL
  ```

  Your notes should be under the footer's line. Add the following to initiate the footer if it does not yet exist

  ```text
    <br><br><br>
    ---
    YOUR NOTES SHALL BE HERE
  ```

- Try to use readable code, if you have to add more tricky/skilled code then explain it well.

  > **Remember!** Hacker's code **=!** Cryptic code

#### Command-line

Use triple ticks to highlight your command-line. ex.

```text
    ls
```

### Contributing with Translation

To translate Rubyfu, make sure to

- Create a new branch for your translation.
- Add a sub-directory under Rubyfu's root directory with the name of the language you will translate to.
- Update the `LANGS.md` file
- Copy and paste the content of `en/` folder to your language folder, then translate it.
- Create a Pull Request \(PR\).

Please make sure to mark the repository as **Watch** to keep your translated efforts up-to-date.

### General Contribution

General contributions might be topic requests, proofreading, spelling, book organization and style. All these contributions are welcome; however, they have to be discussed on [Rubyfu issues](https://github.com/rubyfu/RubyFu/issues) - especially things in regards to topics and/or book organization and styling. At the same time don't hesitate to report even a single word observation about the book, it's for you at the end of the day.

> **Note:** Since this book is enhanced dynamically and unordered, it's hard to make the footer notes with an order-series of numbers for the whole book, so -until I find better solution- I'll make the number order separate for each page individually.
