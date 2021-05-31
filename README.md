# progressive-enchancement
le fermier chinois

# The origin of the Tag name

* *H1-H6*

Represent headings and subheadings. These elements rank in importance according to the number in their name. The h1 element is said to have the highest rank, the h6 element has the lowest rank, and two elements with the same name have equal rank.

* *blockquote*

The blockquote element represents a section that is quoted from another source.
Content inside a blockquote must be quoted from another source, whose address, if it has one, may be cited in the cite attribute.

* *q*

The q element represents some phrasing content quoted from another source.

* *img*

An img element represents an image. The image given by the src attribute is the embedded content, and the value of the alt attribute is the img element's fallback content.
The src attribute must be present, and must contain a valid non-empty URL potentially surrounded by spaces referencing a non-interactive, optionally animated, image resource that is neither paged nor scripted.
The img element must not be used as a layout tool. In particular, img elements should not be used to display transparent images, as they rarely convey meaning and rarely add anything useful to the document.

* *hr*

Represents a paragraph-level thematic break. The "paragraph-level" bit means between blocks of text, so it can't be used to separate sections of a site. Instead, hr now separates different topics within a section of prose, or between scenes in a novel.

* *figure*

The figure element represents some flow content, optionally with a caption, that is self-contained and is typically referenced as a single unit from the main flow of the document.
The figure element can be used to annotate illustrations, diagrams, photos, code listings, etc., that are referenced in the main content of the document, but that could, without affecting the flow of the document, be moved away from that primary content — e.g., to the side of the page, to dedicated pages, or to an appendix.

* *caption*

The caption element represents the title of the table that is its parent, if it has a parent and that is a table element.
When a table element is the only content in a figure element other than the figcaption, the caption element should be omitted in favor of the figcaption.

* *table*

The table element represents data with more than one dimension, in the form of a table. Tables must not be used as layout aids.

* *th*

The th element represents a header cell in a table.

* *tr*

The tr element represents a row of cells in a table.

* *td*

The td element represents a data cell in a table.

* *ul*

The ul element represents a list of items, where the order of the items is not important — that is, where changing the order would not materially change the meaning of the list.

* *ol*

The ol element represents a list of items, where the items have been intentionally ordered, such that changing the order would change the meaning of the list.

* *li*

The li element represents a list item. If its parent element is an ol, ul, or menu element, then the element is an item of the parent element's list, as defined for those elements. Otherwise, the list item has no defined list-related relationship to any other li element.

* *div*

The div element has no special meaning at all. It represents its children. It can be used with the class, lang, and title attributes to mark up semantics common to a group of consecutive elements.

* *span*

The span element doesn't mean anything on its own, but can be useful when used together with the global attributes, e.g. class, lang, or dir. It represents its children.

* *a*

If the a element has an href attribute, then it represents a hyperlink (a hypertext anchor). If the a element has no href attribute, then the element represents a placeholder for where a link might otherwise have been placed, if it had been relevant.
The target, rel, media, hreflang, and type attributes must be omitted if the href attribute is not present.

* *header*

Represents the "header" of a document or section of a document. The header element is typically used to group a set of h1–h6 elements to mark up a page's title with its subtitle or tagline. header elements may, however, contain more than just the section's headings and subheadings — e.g., version history information or publication date.

* *footer*

Represents the "footer" of a document or section of a document. The footer element typically contains metadata about its enclosing section, such as who wrote it, links to related documents, copyright data, etc. Contact information for the section given in a footer should be marked up using the address element.

* *em*

Represents stress emphasis of its contents. The level of emphasis that a particular piece of content has is given by its number of ancestor em elements. The 'stress' being referred to is linguistic. If spoken, this stress would be emphasised pronunciation on a word that can change the nuance of a sentence.

* *strong*

Represents strong importance for its contents. Indicate relative importance by nesting strong elements; each strong element increases the importance of its contents. Changing the importance of a piece of text with the strong element does not change the meaning of the sentence.

* *alt*

The alt attribute provides alternative information for an image if a user for some reason cannot view it (because of slow connection, an error in the src attribute, or if the user uses a screen reader).
