Here I practice with markdown.

The eighth word in this sentence is **bold**.

I'm going to type "Stella" in italics - *Stella*.

EDIT - Wait, that didn't work. I see now it's because I ended "Stella" with a quotation mark instead of an asterisk for some reason. I'll fix that now.

*Is this entire sentence in italics?*

I can make a link to [a random post on Medium](https://medium.com/thewashingtonpost/pink-starbursts-and-brownie-edges-how-our-quirky-preferences-are-driving-the-future-of-snacking-d9d7aa3a6853)

Okay, so I needed to use the .md extension in the filename to cause the markdown (markeddown?) text to display as formatted text.

More stuff I'll try to do
This is from the [GitHub guide to markdown](https://guides.github.com/features/mastering-markdown/)

Here's a list--

1. Lists
2. Piles
3. Sets

Here's a bulleted list, hopefully with sub-bullets--

Wait, first, what happens when you don't put a space after the - or * ?
  A: Oh, right. An asterisk puts things in italics. Wait, no, one asterisk is for italics. Two is for bold. But so then the questions are--
  
          1. What happens when you don't use a space after the hyphen?
                *A. Looks like you get NO bullets. Also, all not-bullets appear on the same line*
            1a. Is this text more faint than the rest?? Why?
                *A. Looks like this list ended up in its own box with a scroll bar for some reason*
          2. What happens when you mix asterisks and hyphens?
                *A. You still get bullets for each. BUT, it looks like asterisk bullets get some extra space between them, while hyphen bullets are single-spaced* Actually, it looks like hyphen bullets get extra space above them only, not below.
          3. Also, when text is formatted like this (in its own box with a scroll bar), it doesn't look like things can be italicized. See above, where the Answers ("A.") are preceded by asterisks but aren't in italics. Also see here-- *I'd've thought this would be in italics, but it isn't in italics." And what about here-- **Is this bold? I bet it's not bold. But I don't really know why. Or, I assume it's because it's in this box thing, but I don't know what the box thing is called or what its function is**
          

Asterisk with space-- 

* Bullet
* Another one
  * More detail about another one
  
  Asterisk with no space-- **Bad example**
  
*Bullet
* Another one
  * More detail about another one

Hyphen with space--

- Bullet
- Another one
  - More detail about another one

Hyphen with NO space--

-Bullet
-Another one
  -More detail about another one

Mixed hyphens and asterisks [hyphen, asterisk, hyphen]

- Bullet
* Another one
  - More detail about another one
  
  **Images**
  
  Apparently I can embed images that have hyperlinks. I'll try.
  ![Image of Carlos sleeping this morning](https://lh3.googleusercontent.com/kbBdTOxDOugFrOLcgQ3dSISd8QA-azuw_biwdGUDL8aA2GICVGKxG-ieVDJm7k9g3-7N80YyTcEqBSt5tqTUApdPafsIEKG-ti-3z6IvCXcTYll3pTrDgsCZG7O8fv7Nt9sl4njg6OTAqQiOflYbmGu0Mwlznkgp2SgKwnhc7QoOz2rAU9FspqJSkKBVbvaUzTgTnHOTrkXwCTdqH3jhYj4kXyWknO_aHhdWTb28YUp-1q1Po60Iac_xLFaT5TU0eKBDkyuVhMcw9QEfugnOEHNhM5ArVkaNiCDKAMysRgoJS5A9K5AZvm4y9dQ1h8il_ewfuAXzoCBtikaUoVCue2PUmZlggNrfN_4IYaekuU7X56xpW5C4s2BJcS2reUKNgzo40N6lRqM33nRsclvz6hw2bqvpxqs1ty9hcRyvsafsd8dWy4YdgawqRG66I6iapEm8clgw7Mj_abLc3NEAnoVpogXvHQaEQJPxU-_pHfjt4VZpA9b5LZdqtrkmgvBeA_ees_rnJG6Lpqv9BAw--jmNnh8iiobn0ACWAfVgAVjQ0Wr7yZVzCfZqFuxWd4HCQx1_OZ_kIXczPRP7mdhnttO_CABOHMVJkgQNLI6p=w1279-h960-no)
  
Looks like the exclamation point that precedes the square brackets is what makes the image an embedded image instead of a link to the image. I wonder how to make the image smaller?

**Headings + quotes**
So there are six different heading sizes. Start a line with # through ######

# This is a big heading, I think
Here's the stuff under it

## This one is probably smaller
Stuff

### Third-tier heading
blah

#### FOUR!
four

##### feefth
5

###### Little heading?
maybe

Looks like the first two heading sizes are displayed with a line under them.

*Displaying a quote*
Put a greater-than symbol (>) at the start of the line--

> The stapler on my desk that I'm looking at is one of three staplers on my desk.
> - Me

QUESTION - The line "> - Me" displays as a bullet (albeit a quoted one). But in the GitHub markdown guide, it displays as part of the quote. I guess the answer is to not put it on a separate line. I'll try--

**On same line**
> The stapler on my desk that I'm looking at is one of three staplers on my desk. - Me

**On next line (should show up as not a quote)**
> The stapler on my desk that I'm looking at is one of three staplers on my desk. 
- Me

A. Yeah, not quoted. But it displays as a bullet. So I guess I need to remove the space after the hyphen.

**Like I just said**
> The stapler on my desk that I'm looking at is one of three staplers on my desk. 
-Me

A. So that put the "-Me" (as such) on the same line as the quote. Maybe I need a blank line between the two?

**Trying that**
> The stapler on my desk that I'm looking at is one of three staplers on my desk. 

-Me

A. Yeah, that did it.

Oh, what happens when I don't close the asterisks for bolding text?


**This is some bold stuff

The line above starts with two asterisks, but I never closed them. IS THIS LINE BOLD?

A. Neither the open-ended two-asterisked line nor the following line is bold. So you must close the bold tag (tag?)

I DUNNO HOW TO CODE YET

# Other stuff

Use @ tags to direct commments. I'll try me so I don't bug anybody I don't know-- @mattnumber - Do something productive!!!

Task lists--

- [ ] Incomplete item
- [x] complete item

**What happens if I put something other than an x in the brackets?**

- [y]
- [elbow]

More--

I copied this directly from the GH markdown guide--

> When you include a task list in the first comment of an Issue, you will see a helpful progress bar in your list of issues. It works in Pull Requests, too!

And, of course emoji! :sparkles: :camel: :boom:

:octopus: :dog: :bull terrier:

Bull terrier is not an emoji.

**More more**

Q. Is inline code the thing I often see with like a background behind some term?

> I think you should use an
`<addr>` element here instead.

A. Yes.

Q. So I guess it's the apostrophes that make it display as inline code?

'bull terrier'

A. No, not apostrophes. Not sure what that character is. Oh, it's the thing you get when you press the tilde key without shift. What's that called? `I have no idea`
EDIT - Now I know. It's the accent grave, or, in programming, [backtick](https://en.wikipedia.org/wiki/Grave_accent). It seems to have different uses in different languages (or environments?)

Q. Also, why didn't @mattnumber display as a link to me?
@mattnumber @ mattnumber 

A. Dunno. Maybe you can't at-tag yourself? I'm gonna find another person's name to try. Then I'll delete it so it doesn't bother them (I hope - sorry to bother you if it bothered you). 

A2. Nope, still didn't work. I'll have to figure that out later.

A3. Oh, here's the answer, I guess--

> Note that some features of GitHub Flavored Markdown are only available in the descriptions and comments of Issues and Pull Requests. These include @mentions as well as references to SHA-1 hashes, Issues, and Pull Requests. Task Lists are also available in Gist comments and in Gist Markdown files.

**More mmmm**
Strikethrough is accomplished by wrapping a word with two tildes--

~~I'm not thirsty~~

## Emojis
[This link](https://www.webpagefx.com/tools/emoji-cheat-sheet/) is to a list of emojis supported by GitHub (and apparently other places)

NO BICYCLES

:no_bicycles: 

That's colon+no+underscore+bicycles+colon
