# TerminalBusinessCard

`curl -sL https://bit.ly/contactbilaly`

### A Terminal Business Card :smirk:

- No piping into the shell is necessary, this is just printing out the contents of business_card into the teminal.

- Uses [Ansi Escape Codes](https://en.wikipedia.org/wiki/ANSI_escape_code) to format the text. in the terminal

- The Aschi art was generated using [Text Fancy](https://textfancy.com/)

- https://bit.ly/contactbilaly is a short link to the file business_card in this repo.


![screenshot](/img/2020-08-18-18-04-40.png)

### Example Of The Formating

```
        escape code
[m      reset. acts the same as [0m 
         reset is used otherwise formatting would continue to the next line.

the number between the '[' and 'm' is the formatting command

[1m     bold formatting
[4m     underline
[90m    Bright Black(Gray)
[97m    Bright White

EXAMPLE:
[1m[94mWeb:        [4mhttps://www.bilaly.me[m 
[bold][bright blue]Web: [underline]https://www.bilaly.me[reset]


the escape code appears incorrect in this example. please refer to the contents 
of the file business_card for the correct character
```
