## LaTeX and Markdown

In the beginning was LaTeX, wrote by Leslie Lemport based on the TeX processor that Donald Knuth wrote. LaTeX was popular among the mathematicians and physicists and indeed anyone who wanted to write in  more than plain text and had to insert equations, tables, citations in the documents to write. But LaTeX authoring is not necessarily easy. While very powerful and indeed LaTeX makes formatting of documents really beautiful with far less effort than what you’d need to make it to work with standard word processors, it also has a steep learning curve. 

On the other hand, word processors are easy to handle, but they are limited. First, these apps do not allow you to port your work easily across devices and systems. Second, as these are based on their proprietary formats (even the open source ones) are not easy to be ported across devices and contexts and would not allow easy working with plain text documents. In other words, you’d not be able to write your paper entirely on a phone and upload it somewhere to mix with some other text you wrote earlier. There is far less portability. So, while they are easy and intuitive, they are not the best solution for this kind of work either. 

We really need to find a middle ground to find that ideal app that will let us write anywhere, everywhere in plain text: leaving us only to write the content, and then the same content can be packaged in as many different ways as we like. We can also write whenever, wherever. LaTeX offers this affordance. Using LaTeX we can write in plain text and the same text can be beautifully formatted for paper based reading, screen based reading, or as slideshow (with beamer). Content is the most important issue here. How that is massaged is another issue.

A very similar approach is also possible with Markdown with some limitations. Markdown has virtually a flat learning curve, easy to learn and use. Like LaTeX it is plain text based. Markdown can be used to author beautiful documents for the web and using Pandoc (a conversion engine), you can convert Markdown documents to LaTeX. So this offers us the best of both worlds. 

Write in Markdown --\> Use Pandoc to convert to LaTeX --\> distribute in LaTeX

The first step is easy: we layout a series of headings and build the structure. This should come from my sense of logic or the structure or my message to the world. I’d like to write in a nice structured way and would like that the world should read my work. I need a structure, and I need a distribution channel. The point is, what elements can we handle in plain text? Let’s see.

The idea is to see if we have tools that can enable me to write in plain text on a web browser and use the web mechanisms to bring in coworkers, or co-authors, and write a piece complete with bibliographic references and all elements easily, moving from situation and context to context yet missing nothing. Everything needs to be as easy as possible. Free, plain text is useful in the sense that people do not necessarily have to learn any crafty and clever tricks to get things to work. It is like using an email communication. You do not need to work in enhanced or rich text format, most of your simple text formatting options would enable you to work \cite{leonard2016text}. 

Markdown itself has come a long way. John Gruber first wrote his definition of markdown and that has some very simple markup properties that more or less work well (see Table 1)

Table 1. Markdown Properties

| Text Marks | Markdown symbols |
|------------|------------------|
| Hashes     | Headers          |
| Dashes     | Bullet Points    |
| Numbers    | Numbered list    |
| Brackets   | Hyperlinks       |
| Bang       | Figures          |

This was it, pretty much. Over time, people added more embellishments to the Markdown and it became easy for anyone to author anything using markdown. Things got a further boost with John Macfarlane and his addition of [Pandoc](http://pandoc.org). Using Pandoc, you could actually transform any document to any other format. There is a wide range of such changes possible and you should check out this website to use. Leijen (2010) wrote Madoko, a great Markdown based scholarly writing environment, but it has a bit of learning curve \cite{leijenmadoko}. Tai-Yi-Lin's [Scholdoc](http://scholarlymarkdown.com/) is another great trial to see how pandoc and scholarly markdown can be brought together. The multimarkdown app by Fletcher Penney is another tool that you can use to write complex texts with Markdown. JATSDOWN and pubref is another project to author everything in Markdown \cite{johnston2016jatdown}. Yet this list is by no means exhaustive and new and updated apps and sites are being added by the day. 

So, the point is that, it is now possible to write in Markdown (entirely in plain text) and use the same content in as many different ways as possible. Writing a plain text document and creating a set of slide decks from the same content is possible. This not only saves time but it also makes it contextual to move back and forth. 

## What are the tools and workflows that can make it happen?

Steps:
1. Write in Markdown (hundreds of Apps, but you can just about use anything to write in Markdown)
2. Convert the Markdown to LaTeX (use Pandoc to convert Markdown to LaTeX)
3. Provide co-workers with a copy of Markdown
4. Use Git to control versions, so that there is only one version that everyone can work on. It is ideal that this version should be live at some place where your coworkers can edit the document seamlessly
5. The referencing will be based on bibtex

## The desirable properties of this workflow

The whole system will need to be as intuitive as possible. A free open source but the source is also freely sharable with the coworkers. Yet when needed, the document will need to be private so that the data and the analyses can be shared secretly or with sufficient confidentiality. Further, coworkers and coauthors may not like to create separate accounts, so while we keep the documents are kept at a site (that in turn can be shared), this document can also be freely edited by anyone who should have an access. Otherwise the document is hidden from public view till such time as it is ready. 

At the same time, the document should be readable on screen, and should have a seamless appearance with correct formatting when presented in paper. The document should have metadata that should be easy for journal articles and web databases to archive and will make it easy for discovery. 

There are quite a few recommendations, and we know that the lingua franca for web based scholarly presentations are PDF documents. Therefore, we need a workflow that should make it easy for us to write using open source free tools where the confidentiality of data can be preserved at will, plus we should be able to distribute the text freely with colleagues and back and forth. Plus, we should be able to insert figures, tables, special characters, equations, everything seamlessly in the document and can work.

## What are some of the existing solutions?
A common approach is to use word processing/presentation software/specialised software solutions. But to achieve everything, we need suites:

1. We run the analyses in our software of choice
2. We export the outputs to the word processor
3. We keep our spreadsheets in the form of matrix based documents (visual documents)
4. Our presentations are based on specialised software
5. The diagrams will need specialised software to work
6. The collaboration is usually based on sharing of documents back and forth
7. The version control can be web based or not
8. Version control can be opaque

Using word processing, presentation software in different systems and keeping them fragmented doesn’t help. Also the opacity in the process does not go well with the principle of writing once and transparency. Byrnes (2013) have argued that the four pillars of scholarly publication are 

1. an ecosystem of scholarly products; 
2. immediate and open access; 
3. open peer review; and 
4. full recognition for participating in the process

For this to be realised, we also need our tools that are free, open sourced, and can be used everywhere and can inter-operate \cite{Kwts0NlF}. Let’s see some tools we have that we can use for this purpose. 


## A comparison of tools

## Workflow

- Analyse in R
- Write in markdown
- Present using Beamer
- Version control in Git
- How do we share and collaborate?