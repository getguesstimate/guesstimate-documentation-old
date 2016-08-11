# Facts

*Facts are available only to organizations with private plans.*

Have a few similar metrics that are used in multiple sheets?  You can use facts to have some constants that will be similar among all of your models.

Organization level facts are currently all private and are only available for use in private models.

### Creating & Editing Facts

Each fact has a ** value**, **name**, and **hashtag**. 

The **value** is a numeric value that represents the current expectation or known value for the fact.  For instance,

``34.8``,

or

``40K to 43K``.

The value can be a data input. It cannot be a function of other facts. Also, if this is a range, you will not be able to choose between Normal, Lognormal, and Uniform distributions.

The **name** is whatever you want to use to refer to the fact. It is only used for your own reference.

The **hashtag** is what you can use to refer to the fact inside of a function.  For instance,

``= #monthly_revenue / 12 ``

Facts can be simply added or edited. They are findable on the organizations' page. We suggest being careful with deleting facts: while this is possible, if you have a model that uses that fact, that model may break.

### Using Facts

Facts are simple to use in models.  In a function, type the hashtag that represents a fact in order to refer to it.  This should auto-complete, so after typing the first few characters, you can click **TAB** to complete the word.  This is sometimes a bit buggy; if there are issues, we suggest copying & pasting the name.

In the case that the fact does not exist any more, there should be an error that indicates this.
