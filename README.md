# Google-SwiftFormat-Config
`SwiftFormat` config compliant with Google Swift Guideline 

## What 

This repository contains ready-to-use `.swiftformat` config, which helps to keep swift code style compliant with Google Swift Guideline. 

## Why 

Setting a formatter with code style rules has many advantages: 
- Keeping code clean and readable :sparkles:
- Similar-looking code no matter which team member developed it :blue_book: :green_book: :orange_book:
- Not wasting time on manual code formatting, meaningless code reviews ("break this line, please") or arguing over the rules :hourglass:

I couldn't find any ready-to-use public template I could just copy and paste into new project, instead of thinking about it every time :shrug:

There are few popular Swift style guidelines. I decided to pick Google's one, as it has hard line-length constraint (from the experience, lack of this constraint led to unreasonably long lines in code): [Read the guideline](https://google.github.io/swift/)

## How to use 
1. Integrate SwiftFormat into your project: [SwiftFormat repository](https://github.com/nicklockwood/SwiftFormat)
2. Download `.swiftformat` file and put it in your project root 

## Additional notes

The file contains mandatory rules (explicitly set in the guidelines), as well as additional rules (those not being specified in the guideline, but helping to keep the codebase clean and minimize redundant code). 

Because of the limited formatter abilites, some rules were not implemented 1:1 accordingly to the guideline (e.g. `@modifiers` are always on the separate line, even though the guideline allows to keep them inline of they don't have any arguments). 

The guideline covers much more than formatter rules - naming convention, code structure and others. I strongly encourage you to read it and keep it in mind during the development :brain:

If you spot some rule being against the guideline, or you have any other concerns, please let me know :sunflower: 
