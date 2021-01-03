# Summary

## Text  

 

** HTML ** elements are used to describe the structure of the page (e.g. headings, subheadings, paragraphs). X They also provide semantic information (e.g. where emphasis should be placed, the definition of any acronyms used, when given text is a quotation). 

 

The (<s>) element indicates something that is no longer accurate or relevant (but that should not be deleted). 

 

The( <ins> )element can be used to show content that has been inserted into a document, while the (<del>) element can show text that has been deleted from it. 

 

The element has quite a specific use: to contain contact details for the author of the page. It can contain a physical address, but it does not have to. For example, it may also contain a phone number or email address. 

 

The first time you explain some new terminology (perhaps an academic concept or some jargon) in a document, it is known as the defining instance of it. The element is used to indicate the defining instance of a new term 

 

When you are referencing a piece of work such as a book, film or research paper, the element can be used to indicate where the citation is from. In HTML5, should not really be used for a person's name — but it was allowed in HTML 4, so most people are likely to continue to use it. 

 

If you use an abbreviation or an acronym, then the element can be used. A title attribute on the opening tag is used to specify the full term. 

 

The element is used for shorter quotes that sit within a paragraph. Browsers are supposed to put quotes around the element, however Internet Explorer does not — therefore many people avoid using the element. 

 

The( <blockquote> ) element is used for longer quotes that take up an entire paragraph. Note how the (<p>) element is still used inside the <blockquote> element 

 

The element indicates emphasis that subtly changes the meaning of a sentence. 

 

The use of the element indicates that its content has strong importance. For example, the words contained in this element might be said with strong emphasis 

 ---

## -CSS-

 

CSS treats each HTML element as if it appears inside its own box and uses rules to indicate how that element should look. X Rules are made up of selectors (that specify the elements the rule applies to) and declarations (that indicate what these elements should look like). X Different types of selectors allow you to target your rules at different elements. X Declarations are made up of two parts: the properties of the element that you want to change, and the values of those properties. For example, the font-family property sets the choice of font, and the value arial specifies Arial as the preferred typeface. X CSS rules usually appear in a separate document, although they may appear within an HTML page. 

 

 ---

 [CSS](data:image/jpeg;base64,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)

## JAVAScript 

 

A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a statement. Statements should end with a semicolon. 

 

You should write comments to explain what your code does. They help make your code easier to read and understand. This can help you and others who read your code. 

 

* An array is a special type of variable. It doesn't just store one value; it stores a list of values 

 

'You create an array and give it a name just like you would any other variable (using the var keyword followed by the name of the array). The values are assigned to the array inside a pair of square brackets, and each value is separated by a comma. The values in the array do not need to be the same data type, so you can store a string, a number and a Boolean all in the same array. This technique for creating an array is known as an array literal. It is usually the preferred method for creating an array. You can also write each value on a separate line'

 
[Javascript](https://cdn.uconnectlabs.com/wp-content/uploads/sites/25/2020/04/J.png)
 