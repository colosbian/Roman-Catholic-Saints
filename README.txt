I. ID attribute values

	admin-forms- Applied to a DIV tag. A set of FORMs for creating/deleting pages.

	saints- Applied to a DIV tag. The list of saints in this representation. This list may contain only one saint.
 	
	search- Applied to a DIV tag. A FORM for searching across saints.


II. Class attribute values

	all- Applied to a UL tag. A list representation. When this element is a descendant of DIV.id="saints" it may have one or more LI.class="saint" descendant elements

	feast- Applied to a SPAN tag. Contains the feast day of a saint in text.

	miracles- Applied to a SPAN tag. Contains text description of the miracles of a saint.

	name- Applied to a SPAN tag. Contains the saint name.

	page-delete- Applied to a FORM tag. A link template for deleting a page.

	patronage- Applied to a SPAN tag. Contains text description of the patronage of a saint.

	place- Applied to a SPAN tag. Contains text description of place associations of a saint.

	prayer- Applied to a SPNA tag. contains the text of a prayer.

	saint- Applied to a LI tag. A representation of a single saint. It may contain the following descendant elements:
		A.rel="saint"
		SPAN.class="feast"
		SPAN.class="miracles"
		SPAN.class="patronage"
		SPAN.class="place"
		SPAN.class="saint-type"
		SPAN.class="time-period"

	saint-create- Applied to a FORM tag. A link template to create a new saint page.

	saint-edit- Applied to a FORM tag. A link template for editing the saint profile page.

	saint-img- Applied to a IMG tag. A reference to an image of a saint. 

	saint-type- Applied to a SPAN tag. Contains text description of the saint type (priest, martyr, apostle, etc.).

	search- Applied to a FORM tag. A link template to search over all of the saints. 

	subpage-create- Applied to a FORM tag. A link template for creating a new subpage.

	subpage-edit- Applied to a Form tag. A link template for editing a subpage.
	
	time-period- Applied to a SPAN tag. Contains dates of a saint's birth or death, or an approximation if specific dates are unknown.


III. Name attribute values

	Anywhere- Applied to an INPUT[text] element. A keyword to search all fields for.

	delete- Applied to an INPUT[checkbox] element. An option to delete the page.

	feastday- Applied to an INPUT[select] or [text] element. A day of a month.

	feastmo- Applied to an INPUT[select] or [text] element. A month of the year.

	Miracles- Applied to an INPUT[text] element. A type of miracle.

	Name- Applied to an INPUT[text] element. The canonical name of a saint.

	Patronage- Applied to an INPUT[text] element. The patronage of a saint.
	
	Place- Applied to an INPUT[text] element. A place associated with a saint.

	saint-img- Applied to an INPUT[file] element. An image of the saint.

	subpage- Applied to an INPUT[text] element. The name of a saint subpage (bio, miracles, prayers).

	text- Applied to an INPUT[text] element. The body of text of a saint subpage.

	Time- Applied to an INPUT[text] element. The time period in which a saint lived. May be a specific date, a range of dates, or a century.

	Type- Applied to an INPUT[text] element. The "type" of a saint as specified by the Catholic Church (marytr, apostle, Doctor of the Church, etc.).


IV. Rel attribute values
	
	bio- Applied to an A tag. A reference to a saint's miracle subpage representation.
	
	index - Applied to an A tag. A reference to the starting URI for the service.
	
	miracles- Applied to an A tag. A reference to a saint's miracle subpage representation. 
	
	prayers- Applied to an A tag. A reference to a saint's prayers subpage representation.
	
	saint- Applied to an A tag. A reference to a saint (profile) representation
	
	search- Applied to an A tag. A reference to the search FORM.
