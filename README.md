![Sticker Sheet](https://c1.staticflickr.com/1/688/33320753446_390dd106c6_h.jpg)
SLDS Sticker Sheet
========
Salesforce Lightning Design system design kit for Sketch. A Style based design system leveraging symbol's. This system will encourage consistency between design teams, while making the design process faster and easier.
**This system will ensure design consistency and continuity across teams.**

# Basic usage

### **Method 1:** Copy &amp; Paste Symbols as needed
A quick way to get going is to simply copy and paste components from the **SLDS-stickersheet.sketch** into your working file. The one downside to this method is all the accompanying styles will NOT be included.

For example if we copy an input symbol in the default state, and then if we want to change the input to an error state, the error styles don't currently exist in our working file.

So we would then need to copy the error symbol and past it into our working file well. One this is done we can simply delete it from our page as it was automagically added to the symbols page and you now have access to that style!

*[Insert image here]*


### **Method 2:** Starting From Scratch
If you know you may need access to the majority of the styles, and wish to start totally from scratch use the included **SLDS-Starter.sketch**

The SLDS Starter is a blank file, but has all the symbols already added for you in the symbols page. However, many of the SLDS components are not single symbol entities, a table for example has to be built.

*[Insert image here]*

# Using Symbols
This system is entirely based upon symbols. The advantage of this is updating styles becomes more modular, just the way CSS works conceptually. Additionally, this keeps file sizes significantly smaller, as components are typically a single symbol, referencing other symbols.

Any symbol can be added from the symbols menu:
**Insert -> Symbol -> {symbol name}**.
There you will find all major symbols listed alphabetically.

Or if using [Sketch runner ](http://sketchrunner.com/), which i highly recommend, you can just type the name of the symbol you are looking for.

![How to](http://bradysammons.com/SLDS_images/symbols-menu.png)


### Symbol Overrides
Symbol overrides are the heart of this system, as everything is style based. Not all symbol structures are created identical, however they all maintain some level of consistency.

Once a symbol has been added to the page you can select it and use the **"Overrides" in the right sidebar to control the appearance of the symbol.** Some symbols will have more overrides than others, its just depends on the symbol.

**Most of the symbols will contain the following overrides at a minimum:**
- **:black_nib:Text:** Change the text value.
- **:art:BG:** Change the background color.

**Some symbols like buttons will have more overrides than others.**
- **Text Style:** Change the text style.
- **↳:black_nib:Text:** Change the text value
- **Icon:** Change the icon - Center icon is default on buttons.
- **:triangular_ruler:Brdr:** Border color of the button
- **:bulb:State:** Add hover state
- **:art:BG:** Change the background color.

**"↳" Denotes a style relationship.** If we take the button example below, the text style will control the appearance of the text value.

![How to](http://bradysammons.com/SLDS_images/howTo.gif)

# Object Structure

### Buttons
Rename Multiple layers at once. You can access it from the menu
